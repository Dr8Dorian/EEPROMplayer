# EEPROMplayer
This is the circuit design behind [Ioana Vreme-Moser's Mineral Amnesia](https://www.ioanavrememoser.com/mineral-amnesia) art piece. 

It is an MCU-less 8 Bits audio player. Audio data is read from an UV erasable EEPROM via a CMOS counter clocked with a virable frequency 555 while an UV light slowly erase the data over time. Jumper between the counter and adress of the EEPROM allows for mangling of the sound

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
