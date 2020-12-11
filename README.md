## Adafruit EMC2101 Tempature Sensor and Fan Controller PCB

<a href="http://www.adafruit.com/products/4808"><img src="assets/4808.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit EMC2101 Tempature Sensor and Fan Controller. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4808

### Description

Cooling fans. They're everywhere, and they serve the important purpose of keeping things cool, generally electronics. One might rightfully think: "these fans are pretty good at moving air to keep things cool; maybe I can use one of these neat computer fans to keep my widget frosty" followed closely by throwing up one's hands in confusion at the sight of a 3 or even 4-pin connector. OK, power takes two pins but what are these other pins for and how do I use them to convince this fan to keep my things chilly?

The EMC2101 from Microchip/SMSC is a 1 degree C accurate fan controller with temperature monitoring and it will take care of all of that for you. Those extra pins allow you to set a the speed of the fan, and in the additional pin of a 4-pin connector adds a tachometer output that allows you (or the EMC2101) to monitor the speed of the fan to make sure it's working as expected. In addition to allowing you to control a fan, the EMC2101 includes an internal temperature sensor, as well as connections for an external temperature sensing diode. If you use an external temperature sensor, you can even configure a look up table (LUT) that allows you to set different fan speeds depending on the temperature, and the EMC2101 will automatically adjust the speed depending on the temperature.

This neat little chip can easily be used to help provide cooling or ventilation to your next project. You might even be able to use it to help quiet down an existing project or hack a noisy piece of electronics that has a loud fan. By allowing you to run a fan at slower speeds when cooling needs are moderate, the EMC2101 can help ease the noise pollution caused by fans running at full speed.

Delivered to you on our custom Stemma QT form factor PCB, the Adafruit EMC2101 breakout is ready to help you integrate a fan into your project by making it easy to use with a range of devices. A voltage regulator and 5V tolerant pins allow you to use it with 3.3V or 5V microcontrollers or single board computers. The included included SparkFun qwiic compatible STEMMA QT connectors for the I2C bus allow you to make easy solderless connections to your controlling device, and the standard headers make breadboard prototyping easy.Our libraries, wiring diagrams, and example code for Arduino, CircuitPython and Python complete the package. Fantastic!




### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
