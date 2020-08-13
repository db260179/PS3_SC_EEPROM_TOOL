# PS3_SC_EEPROM_TOOL
Syscon EEPROM Utility for PS3

Based on SPIway by PS3 developer judges <judges@eEcho.com> https://github.com/hjudges/NORway
This tool allows for Read/Write abiltiy on older PS3 Syscon EEPROMs

## Why?
Why not, dont have a bus pirate and wanted wiring simpler without voltage division for 5v logic level on the Arduino based EEPROM tool. Teensy 2.0++ is nicer imo

## Requirements

Ubuntu 18.04+ Required packages:

`sudo apt-get install gcc-avr avr-libc avrdude python-serial python-crypto`

Windows:

`http://winavr.sourceforge.net/download.html`

## Compile code

`make all` - all code build

`make hex` - to send to the Teensy 2.0+

`make clean` - to cleanup built code

## TODO:
  - Include a wiring guide.
  - Status check broken?
