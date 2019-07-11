# Frunkduino
An Arduino-compatible board that fits in the Frunk of the Valve Index.

The heart of this board is an Adafruit Feather M4, but the additional space offered by the frunk has been used to add some additional features. Namely:

* A larger prototyping area with bus bars for power
* A SparkFun Quicc connector for adding I2C devices easily
* A beefier 3.3v regulator capable of delivering 1.2A
* An N-Channel MOSFET capable of sourcing 1.3A, to power motors or high power LEDs
* Second row of header breakouts, so you can solder to pins even after headers are installed
* A full sized USB-A connector positioned to plug directly into the Index

The MCU is an ATSAMD51 running at 120MHz. I figured a high-end headset needs a high-end MCU :)

All created in the free version of Diptrace. A new Arduino board definition will be required to use the MOSFET, which does not exist as of yet.

![Image of Frunkduino](https://github.com/MadlyFX/Frunkduino/blob/master/Photo.jpg)
