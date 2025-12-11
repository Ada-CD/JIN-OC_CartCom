# CartCom

This is a Unity project that loads a [PICO-8](https://www.lexaloffle.com/pico-8.php) cartridge from a physical EEPROM,
via an Arduino.
This has been tested with Unity ***6000.0.63f1***.

It allows connecting to a serial port from the interface, loading a cartridge via the serial port and starting
the PICO-8 console with it.  
Thus, __it is necessary__ to provide the path to a PICO-8 executable in the inspector to be able to play the games !

The goal here is for students to fill in the blanks regarding the communication between the Arduino and the EEPROM,
and the Arduino and Unity.

The corresponding Arduino code is in :
 - [Arduino/SendCart](Arduino/SendCart), for reading from the EEPROM and sending cartridges to Unity,
