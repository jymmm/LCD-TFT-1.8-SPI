# 2016-03-04
#
# LCD-TFT-1.8-SPI
#

This is in reference to the cheap chinese 1.8" TFT LCD SPI with SD CARDSLOT 128*160 clones off
aliexpress/ebay and use with Arduino IDE, Arduino Nano, and the 'Adafruit ST7735 Library' as 'hardware spi'.

<pre>
PINOUT (TFT ... Arduino Nano)[dupont cable color]:
--------------------------------------------------
01 GND ..... GND [BLK]
02 VCC ..... +5VDC [RED]
03 NC   
04 NC
05 NC
06 RST ...... D9 (TFT_RST) [GRN]
07 A0 ....... D8 (TFT_DC) [ORG]
08 SDA ...... D11 (TFT_MOSI) [BRN]
09 SCK ...... D13 (TFT_SCLK) [BLU]
10 CS (TFT).. D10 (TFT_CS) [VIO]
11 SCK
12 MISO
13 MOSI
14 CS (SD)
15 LED(+) .... +5V or +3.3 VDC (LED backlight VCC) [WHT]
16 LED(-) .... GND (LED backlight GND) [GRY]
--------------------------------------------------
</pre>


NOTE: arduino nano pins D8 and D9 are REVERSED between the adafruit library and this link:<br>
http://blog.simtronyx.de/en/a-1-8-inch-tft-color-display-hy-1-8-spi-and-an-arduino/

