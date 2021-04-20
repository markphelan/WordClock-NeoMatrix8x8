 WORD CLOCK - NeoMatrix 8x8 Desktop Edition
================
 by [Andy Doro](https://andydoro.com/) & [Dano Wall](https://github.com/danowall)
 
https://andydoro.com/wordclockdesktop/

[Adafruit Learn Guide](https://learn.adafruit.com/neomatrix-8x8-word-clock/)

A word clock which uses NeoPixel RGB LEDs for a color shifting effect.

(Modified by Mark Phelan to run on Wemos D1 Mini)

Hardware:
-------
 
 - Wemos D1 Mini
 - DS3231 RTC
 - [NeoPixel NeoMatrix 8x8](https://www.adafruit.com/products/1487)
 - laser cut faceplate & enclosure
 
Software:
-------
 
This code requires the following libraries:
 
 - [RTClib](https://github.com/adafruit/RTClib)
 - [DST_RTC](https://github.com/andydoro/DST_RTC)
 - [Adafruit_GFX](https://github.com/adafruit/Adafruit-GFX-Library)
 - [Adafruit_NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel)
 - [Adafruit_NeoMatrix](https://github.com/adafruit/Adafruit_NeoMatrix)


Wiring:
-------

 - Connect RTC to Gnd = D4, 5v = D3, SDA = D2, SCL = D1
 - Solder NeoMatrix 5V to Trinket 5V, GND to GND, DIN to D8.
 

grid pattern:
-------

 ```
 A T W E N T Y D
 Q U A R T E R Y
 F I V E H A L F
 D P A S T O R O
 F I V E I G H T
 S I X T H R E E
 T W E L E V E N
 F O U R N I N E
 ```
 
Acknowledgements:
  - Thanks [Dano](https://github.com/danowall) for faceplate / 3D models & project inspiration! 
 

