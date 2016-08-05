#Kinoma Create/Arduino I<sup>2</sup>C sample

##Contents

- **arduino-create-i2c-test** folder contains sketch to run on Arduino (tested on an Arduino Uno)
- **create-arduino-i2c-test** folder is KinomaJS app to run on Kinoma Create. Note that all it does it send text to the Arduino; nothing will appear on the screen.


##Setup Instructions

**Before wiring**, open Front Pins app on Kinoma Create and set configuration as follows:

- Pin 51: SDA
- Pin 52: SCL
- Pin 53: GND

**Make sure left side uses 5V power (not 3.3V, as it does by default).** Hit Apply. Then wire Arduino to Kinoma Create as follows:

- Arduino A4 (SCL) to pin 51
- Arduino A5 (SDA) to pin 52
- Arduino GND to pin 53
