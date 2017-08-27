# ESP8266 hacked-HomeEasyByNoopy
This is a version of noopys code with bits (the hardware timer calls) commented out to allow compilation on an ESP8266. Note doing this means you can not use the recieve function only send works. You will need an arduino to sniff the correct codes for your devices.

Manage your lights and rolling shutters with Arduino !

This is an implementation of the HomeEasy protocol. You can listen, or emit a signal. Use the https://www.itead.cc/433mhz-rf-link-kit.html module

## Installation
Clone this repo in the ``libraries`` folder of Arduino source workspace. Launch Arduino, and try the examples from the menu. Have fun !

## Usage
To test the example, pin 0 is connected to the receiver, pin 4 is connected to the emiter
(Note on my board anyway the D4 pin is accessed from pin 2)

![schematic](https://raw.githubusercontent.com/landru29/HomeEasyByNoopy/master/homeEasy.jpg "Schematic")
