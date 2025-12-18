# NoMORE - software to make a [RCM](https://github.com/RCMgames) or [NoU](https://www.alfredosys.com/) into an I2C controlled expansion board

# work in progress
expect breaking changes

## Questions?

## Programmer Website (start here)

## Examples

## Compatibility
* [Alfredo Systems NoU3](https://www.alfredosys.com/products/alfredo-nou3/) - untested
* [Alfredo Systems NoU2](https://www.alfredosys.com/products/alfredo-nou2/) - untested
* [RCM_V4](https://github.com/RCMgames/RCM-Hardware-V4) - untested
* [RCM_BYTE](https://github.com/RCMgames/RCM-Hardware-BYTE) - untested
* [RCM_Nibble](https://github.com/RCMgames/RCM-Hardware-Nibble) - untested

### ESP32 Microcontrollers
* ESP32 DevKitC with 38 pins
* Adafruit ESP32s3 QT Py with no psram (#5426)
* Adafruit ESP32s3 QT Py with 2MB psram (#5700)
* ESP32 DevKit with 30 pins (NoU2)
* Alfredo Systems NoU3


## Acknowledgements
* [Alfredo Systems](https://www.alfredosys.com/) for making open source libraries for their NoU2 and NoU3 boards
* [PlatformIO](https://registry.platformio.org/platforms/platformio/espressif32) for compiling
* [arduino-esp32](https://github.com/espressif/arduino-esp32)
* [esptool-js](https://github.com/espressif/esptool-js)
* [ArduinoJson](https://arduinojson.org/) library for using JSON data in Arduino by Benoit Blanchon
* [ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer) web server and web sockets library for ESP32 by @me-no-dev
* [FastLED](https://github.com/FastLED/FastLED) library for controlling the RGB led on QT Py
* [gobabygocarswithjoysticks/programmer](https://github.com/gobabygocarswithjoysticks/programmer) the RCM programmer reuses code from this project for programming ESP32s
* [JMotor](https://github.com/joshua-8/JMotor) library for motor control by @joshua-8
* [RCMgames](https://github.com/rcmgames) for robot control boards and software
