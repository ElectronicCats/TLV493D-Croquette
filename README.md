# Electronic Cats Croquette TLV493D

<a href="https://electroniccats.com/store/tlv493d-croquette/">
  <img src="https://electroniccats.com/wp-content/uploads/badge_store.png" height="104" />
</a>

The 3D magnetic sensor TLV493D-A1B6 offers accurate three-dimensional sensing with extremely low power consumption in a small 6-pin package. With its magnetic field detection in x, y, and z-direction the sensor reliably measures three-dimensional, linear and rotation movements. Applications include joysticks, control elements (white goods, multifunction knops), or electric meters (anti tampering) and any other application that requires accurate angular measurements or low power consumptions.
The integrated temperature sensor can furthermore be used for plausibility checks.

Key features are 3D magnetic sensing with a very low power consumption during operations. The sensor has a digital output via 2-wire based standard I2C interface up to 1 MBit/sec and 12 bit data resolution for each measurement direction (Bx, By and Bz linear field measurement up to +-130mT).

## Key Features and Benefits
* Integrated temperature sensing
* Low current consumption of 0.007 µA in power down mode and 10 µA in ultra low power mode
* 2.7 to 3.5 V operating supply voltage
* Digital output via 2-wire standard I2C interface
* Bx, By and Bz linear field measurement up to ±130 mT
* 12-bit data resolution for each measurement direction
* Resolution 98 µT/LSB
* Operating temperature range from -40 °C to 125 °C
* [GUI](https://www.infineon.com/dgdl/Infineon-Software-for-3D-Magnetic-Sensor-2Go%20incl.%20out-of-shaft_05_06-SW-v05_06-EN.zip?fileId=5546d4626102d35a01614626f9644e4e) for free download as well as integration in Arduino IDE with this repository


## Usage

Please see the example sketches in the repository [Arduino Library](https://github.com/Infineon/TLV493D-A1B6-3DMagnetic-Sensor) in this library to learn more about the usage of the sensor.


### Usage Electronic Cats TLV493D with Arduino Library 

The Electronic Cats TLV493D-A1B6 3DMagnetic is a standalone break out board. You can connect it easily to any microcontroller of your choice which is Arduino compatible and has 3.3V logic level (please note that the Arduino UNO has 5V logic level and cannot be used without level shifting).

* [Link](https://github.com/Infineon/TLV493D-A1B6-3DMagnetic-Sensor/wiki) to the wiki with more information

### Processing
This library supports the open-source software [Processing](https://processing.org/) for creating GUIs. It allows you to connect your evaluation board to a PC over serial communication and visualisation of the embedded system. Find out more on the Arduino homepage [here](http://playground.arduino.cc/Interfacing/Processing). The respective files are stored in the /processing folder of this repository. 

### Printables
The TLx493D 3D magnetic sensor family has additional tools which can be directly mounted on top of the evaluation boards. The 3D print data of the [joystick](https://www.infineon.com/cms/en/product/promopages/sensors-2go/#Add-ons-3D-Magnetic-2GO), the [rotate knob](https://www.infineon.com/cms/en/product/promopages/sensors-2go/#Add-ons-3D-Magnetic-2GO) and the [linear slider](https://www.infineon.com/cms/en/product/promopages/sensors-2go/#Add-ons-3D-Magnetic-2GO) can be found in the folder `printables`.

<img src="https://www.infineon.com/export/sites/default/media/products/Sensors/joystick.jpg_708092179.jpg" width=250>

## Board Information, Datasheet and Additional Information

The datasheet for the TLV493D-A1B6 can be found here [TLV493D-A1B6 Datasheet](https://www.infineon.com/dgdl/Infineon-TLV493D-A1B6-DS-v01_00-EN.pdf?fileId=5546d462525dbac40152a6b85c760e80) while respective application notes are located here [Application Notes](https://www.infineon.com/dgdl/Infineon-TLV493D-A1B6_3DMagnetic-UM-v01_03-EN.pdf?fileId=5546d46261d5e6820161e75721903ddd).


## License
![OpenSourceLicense](https://github.com/ElectronicCats/AjoloteBoard/raw/master/OpenSourceLicense.png)

Electronic Cats invests time and resources providing this open source design, please support Electronic Cats and open-source hardware by purchasing products from Electronic Cats!

Designed by Electronic Cats.

Hardware released under an CERN Open Hardware Licence v1.2. See the LICENSE_HARDWARE file for more information.

Electronic Cats is a registered trademark, please do not use if you sell these PCBs.

28 August 2019
