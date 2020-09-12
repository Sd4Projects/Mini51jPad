# Mini51jPad
SAMD51 Project, This board uses the ATSAMD51J chip and can run Arduino or Circuit Python depending how flash is on board is configured.

This project is released under Open Hardware License. All sources files have been uploaded.

For this Pad project I split the network part out onto it's own board.

Mini51JPad features.
 1. CPU is an ATSAMD51J19.
 2. Has a RT6222 buck based power supply, so wider range of power can be used.
 3. Support for external RA8875(Adafruit) with 7 inch TFT and touch screen.
 4. Has MicroSD slot.
 5. Has RTC Clock DS3231 chip with battery backup.
 6. 2 Meg of flash memory GD25Q16C.
 7. 1 NEO pixel.
 8. MCP23008 I/O.
 9. ADS1115 AtoD.
10. MCP4725 DtoA.
11. Buzzer.
12. One 16 pin and one 20 pin external jacks.
13. Has jack for a 10/100 network interface W5500 and supporting builtin 802.3af PoE LTC4267.

![alt text](https://github.com/Sd4Projects/Mini51jPad/blob/master/Mini51jBoardsTop.jpg?raw=true "Boards Top")

Bare board can be ordered from OSH Park. https://oshpark.com/shared_projects/XXBk5137 with project name Mini51jPad_v01a.kicad_pcb or use source files and order from whoever you want.

Bare board can be ordered from OSH Park. https://oshpark.com/shared_projects/uvxaA4xl with project name Mini51jNet_v01a.kicad_pcb or use source files and order from whoever you want.

![alt text](https://github.com/Sd4Projects/Mini51jPad/blob/master/Mini51jBoardsBottom.jpg?raw=true "Boards Bottom")

Flash solder jumper options.

![alt text](https://github.com/Sd4Projects/Mini51jPad/blob/master/Mini51Board_FlashSetup.jpg?raw=true "Flash")

Boards in PLA 3D printed case.

![alt text](https://github.com/Sd4Projects/Mini51jPad/blob/master/Mini51BoardsInCase.jpg?raw=true "case")

program-samd-bootloaders info

https://cdn-learn.adafruit.com/downloads/pdf/how-to-program-samd-bootloaders.pdf?timestamp=1554315784

Bootloader files.

https://github.com/adafruit/uf2-samdx1/releases

See SAMD51J_Board for burning the bootloader. The SAMD51J_Board and this board use the same CPU.

