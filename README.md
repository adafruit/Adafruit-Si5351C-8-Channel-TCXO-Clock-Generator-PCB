## Adafruit Si5351C 8 Channel TCXO Clock Generator - 2.5KHz-200MHz - STEMMA QT PCB

<a href="http://www.adafruit.com/products/6534"><img src="assets/6534.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Si5351C 8 Channel TCXO Clock Generator - 2.5KHz-200MHz - STEMMA QT. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6534

### Description

Never hunt around for another crystal again, with the Si5351C clock generator breakout from Adafruit! This chip has a precision <b>temperature compensated (TCXO)</b> 25MHz crystal reference and internal PLL and dividers so it can generate just about any frequency, from 2.5 KHz up to 200 MHz on CLK0-CLK5, and about 20 kHz to 50 Mhz on CLK6 and CLK7.

The Si5351C clock generator is an I2C controller clock generator with eight outputs. It uses the onboard precision clock - or an external clock - to drive multiple PLL's and clock dividers using I2C instructions. By setting up the PLL and dividers you can create precise and arbitrary frequencies. There are eight independent outputs, and each one can have a different frequency. Outputs are 3Vpp by default but can be configured to be lower via the VDDA/B/C/D breakout pads. The outputs can be accessed either through a breadboard-friendly header or, for RF work, [optional edge-launch SMA connector](https://www.adafruit.com/product/1865) for alternating outputs - so 4 total. The edge launch SMA connectors are sold separately.

To get you going fast, we spun up a custom-made PCB in the [STEMMA QT form factor](https://www.adafruit.com/?q=stemma%20qt%20sensor), making it easy to interface with. The [STEMMA QT connectors](https://learn.adafruit.com/introducing-adafruit-stemma-qt/what-is-stemma-qt) on either side are compatible with the [SparkFun Qwiic](https://www.sparkfun.com/qwiic) I2C connectors. This allows you to make solderless connections between your development board and the Si5351 or to chain it with a wide range of other sensors and accessories using a [compatible cable](https://www.adafruit.com/?q=stemma%20qt%20cable). Onboard 3.3V LDO and level shifters means its ready for use with 3V or 5V power and logic!

[Best of all, we even have a great tutorial and library to get you started! Our code is designed for use with the Arduino-compatible microcontrollers and CircuitPython/Python](https://learn.adafruit.com/adafruit-si5351-clock-generator-breakout) using I2C support.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
