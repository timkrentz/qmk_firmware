# ErgoDox EZ Default Configuration

## Personal instructions
* Build with `qmk_firmware$ make ergodox_ez:tim`
* Flash using teensy_loader_cli with `qmk_firmware$ teensy_loader_cli --mcu=TEENSY2 -w -v ergodox_ez_tim.hex`
* Hit the ol' reboot button, it'll flash then reboot the board

## Changelog

* Dec 2016:
  * Added LED keys
  * Refreshed layout graphic, comes from http://configure.ergodox-ez.com now.
* Sep 22, 2016:
  * Created a new key in layer 1 (bottom-corner key) that resets the EEPROM.
* Feb 2, 2016 (V1.1): 
  * Made the right-hand quote key double as Cmd/Win on hold. So you get ' when you tap it, " when you tap it with Shift, and Cmd or Win when you hold it. You can then use it as a modifier, or just press and hold it for a moment (and then let go) to send a single Cmd or Win keystroke (handy for opening the Start menu on Windows).

This is what we ship with out of the factory. :) The image says it all:

![Default](https://i.imgur.com/Be53jH7.png)