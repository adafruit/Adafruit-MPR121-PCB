## Adafruit MPR121 capacitive touch breakout PCB
<a href="http://www.adafruit.com/products/1982"><img src="assets/1982.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>
<a href="http://www.adafruit.com/products/4830"><img src="assets/4830.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

Add lots of touch sensors to your next microcontroller project with this easy-to-use 12-channel capacitive touch sensor breakout board, starring the MPR121. This chip can handle up to 12 individual touch pads.

The MPR121 has support for only I2C, which can be implemented with nearly any microcontroller. You can select one of 4 addresses with the ADDR pin (or two on the Gator version), for a total of 48 (24 on the Gator version) capacitive touch pads on one I2C 2-wire bus. Using this chip is a lot easier than doing the capacitive sensing with analog inputs: it handles all the filtering for you and can be configured for more/less sensitivity.

This sensor comes as a tiny hard-to-solder chip so we put it onto a breakout board for you. Since it's a 3V-only chip, we added a 3V regulator and I2C level shifting so its safe to use with any 3V or 5V microcontroller/processor like Arduino. We even added an LED onto the IRQ line so it will blink when touches are detected, making debugging by sight a bit easier on you. Comes with a fully assembled board, and a stick of 0.1" header so you can plug it into a breadboard. For contacts, we suggest using copper foil or pyralux, then solder a wire that connects from the foil pad to the breakout.

To make using the MPR121 QT Gator as easy as possible, we’ve put the MPR121 on a breakout PCB in our Stemma QT form factor with a sprinkle of support circuitry to give you options when testing. You can either use a breadboard or the SparkFun qwiic compatible STEMMA QT connectors, and compatibility with 5V voltage levels as commonly found on Arduinos, as well as 3.3V logic used by many other boards like the Raspberry Pi or our Feathers. QT Cable is not included, but we have a variety in the shop for quick plug-and-play support.

PCB files for Adafruit MPR121 capacitive touch breakout. The format is EagleCAD schematic and board layout
- https://www.adafruit.com/product/1982
- https://www.adafruit.com/product/4830

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

All text above must be included in any redistribution

Designed by Limor Fried/Ladyada for Adafruit Industries.
Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution.
See license.txt for additional information.
