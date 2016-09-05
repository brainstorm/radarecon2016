1. Determine the meaning of the EEPROM contents.
2. Write an in-drone flasher (avrdude wrapper?). Not sure about that since AVRdude requires MOSI/MISO/SCLCK,
so perhaps having a custom bootloader that takes the firmware over regular UART and reflashes itself instead?
3. Fork https://github.com/Parrot-Developers/ardrone-opensource and pullrequest a real opensource clone of program.elf and flash_blc.ihex. Start here: https://github.com/cbarox/ardrone.
4. Share binaries with encrypted project files.
