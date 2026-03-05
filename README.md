Arduino Biometric & Scanning Projects
1.Project Overview:
This repository contains the complete implementation details for my hardware projects, including a Biometric Fingerprint Scanner and an I2C Barcode/QR Code Scanner. These projects demonstrate my ability to interface sensors with the Arduino Uno R3 using both Serial and I2C protocols.
2.Source Code & Documentation:
I2C Barcode Scanner: Uses the Wire.h library to communicate with the scanner at address 0x0C.
Fingerprint Logic: Implemented using the AS608 sensor to enroll and search for biometric templates.
Programming: Developed using the Arduino IDE with clear modular logic for reset and data retrieval.
3.Necessary Setup Instructions (I2C Barcode Scanner):
To implement the Barcode Scanner, use the following pin configuration:.
| Scanner Pin | Arduino Pin |
| :--- | :--- |
| SCL | A5 |
| SDA | A4 |
| RST | D7 |
| VDD | 5V |
| GND | GND |
Steps:
Connect the pins as shown in the table above.
Install the Wire.h library in your Arduino IDE.
Upload the provided source code and open the Serial Monitor at 9600 baud to see the scanned data.

