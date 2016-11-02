# Seeed-Studio-Relay-Shield-v3.0
Relay control of higher voltage DC motor with low voltage Arduino using the Seeed shield

Source: http://wiki.seeedstudio.com/wiki/Relay_Shield_V3.0

Introduction

The Relay Shield utilizes four high quality relays and provides NO/NC interfaces that control the load of high current. Which means it could be a nice solution for controlling devices that couldn’t be directly controlled by Arduino’s Digital I/Os. Standardized shield form factor enables smoothly connection with the Arduino. The shield also has four dynamic indicators show the on/off state of each relay. 

Cautions

Place 2 layers of electrical tape on the top of the Arduino's usb connector. This will prevent the relay shield from making contact. Do not operate voltage more than 35V DC.

Interface Function

J1 Interface:
COM1- Common pin
NC1- Normally Closed. Will be connected with COM1 when RELAY1 pin is set low and disconnected when RELAY1 is high; 
NO1- Normally Open. Will be connected with COM1 when RELAY 1 pin is set high and disconnected when RELAY1 is low; 
J2-4 Interface are similar to J1 interface, except that the control ports are RELAY2-RELAY4. 
4 Digital Pins to control 4 Relays: RELAY1-RELAY4 pins could be connected directly with Arduino pin number of 7-4, so that four relays could be easily controlled by the Arduino

Usage

The relay have some practical application. For example: low-voltage control of high voltage; remote control; anti-hearing alarm, automatic temperature alarm; incubators and so on.
