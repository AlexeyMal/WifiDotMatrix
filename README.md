# WifiDotMatrix
 
Wifi-Controlled LED Matrix Display

![](https://github.com/AlexeyMal/WifiDotMatrix/blob/main/IMG_20210123_195425.jpg?raw=true)

Put your Wifi access point data into the code.
The display will show its IP address. 
You can sent the text to display in english, german and russian from any web browser.
I have merged these three languages into one font.

Components required:
1. NodeMCU ESP8266
2. 2x 4-in-1 8×8 LED Matrix(FC_16, Parola, GENERIC or IC_Station) with MAX7219 controller
(3. Arduino IDE to programm the NodeMCU)

Circuit Connections:

Vcc ———— 3v3

GND ———— GND Ground

DIN ———— D7 HSPID or HMOSI

CS or LD ———— D8 HSPICS or HCS

CLK ———— D5 CLK or HCLK
