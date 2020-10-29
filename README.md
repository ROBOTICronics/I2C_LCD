# I2C_LCD
#
Create a custom character (glyph) for use on the LCD: up to eight characters of 5x8 pixels are supported (numbered from 0 to 7).

The appearance of each custom character is specified by an array of eight bytes, one for each row. The five least significant bits of each byte determine the pixels in that row. To display a custom character on the screen, write() its number.

NB : When referencing custom character "0", if it is not in a variable, you need to cast it as a byte, otherwise the compiler throws an error.

See the example below.

lcd.write(byte(0));

while, instead,

lcd.createChar(0, smiley);
---------------------------------------------
https://github.com/ROBOTICronics/I2C_LCD/wiki
