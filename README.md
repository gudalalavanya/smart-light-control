# smart-light-control

*company*:CODTECH IT SOLUTIONS

*NAME*:Gudala Lavanya

*INTERN ID*:CT04WN130

*DOMAIN*:IOT

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTHOSH

**ABOUT**
This project demonstrates how to control an LED light using a microcontroller (Arduino) and a mobile application via Bluetooth communication. The system allows users to turn the LED ON and OFF remotely using their smartphones.
*TOOLS*:Component	Description
Arduino Uno	Microcontroller to process commands
HC-05/HC-06 Bluetooth Module	Wireless communication with mobile
LED	Output device to indicate control
220Ω Resistor	Limits current to protect the LED
Jumper Wires	Connections between components
Mobile Phone	Runs the app to control the LED
**curcuit connection**
Circuit Connection
Wiring the Components
LED

Anode (+) → Arduino Pin 9 (through 220Ω resistor)

Cathode (-) → GND

Bluetooth Module (HC-05/HC-06)

VCC → 5V (Arduino)

GND → GND (Arduino)

TX → RX (Arduino Pin 2 via voltage divider)

**mobile app control**
To control the LED, we can use:

MIT App Inventor App (Custom app for user-friendly control)

Bluetooth Terminal App (Sends '1' and '0' to control LED)

The mobile app will:

Send '1' to turn the LED ON

Send '0' to turn the LED OFF

![Image](https://github.com/user-attachments/assets/945abf60-903c-411d-8f0f-5160abe5253d)

![Image](https://github.com/user-attachments/assets/d1d209d9-0e91-4fac-adf6-339f4b42852a)
