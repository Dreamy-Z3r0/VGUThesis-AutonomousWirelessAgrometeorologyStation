# Source code for the gateway of the Autonomous Wireless Agrometeorology Station

_This source code is built using Arduino IDE version 1.8.19_

## Third-party platform package for ESP8266
> https://arduino.esp8266.com/stable/package_esp8266com_index.json

## Board setup
+ Board: "NodeMCU 1.0 (ESP-12E Module)"
+ Builtin Led: "2"
+ Upload speed: "115200"
+ CPU Frequency: "80 MHz"
+ Flash Size: "4MB (FS:2MB OTA:~1019KB)"
+ Debug port: "Disabled"
+ Debug Level: "None"
+ IwIP Variant: "v2 Lower Memory"
+ VTables: "Flash"
+ C++ Exceptions: "Disabled (new aborts on oom)"
+ Stack Protection: "Disabled"
+ Erase Flash: "Only Sketch"
+ SSL Support: "All SSL ciphers (most compatible)"
+ MMU: "32KB cache + 32KB IRAM (balanced)"
+ Non-32-Bit Access: "Use pgm_read macros for IRAM/PROGREM"

## Library dependencies
+ [thingspeak-arduino](https://github.com/mathworks/thingspeak-arduino) *by* **mathworks**, version 2.0.1
+ [arduino-LoRa](https://github.com/sandeepmistry/arduino-LoRa) *by* **Sandeep Mistry**, version 0.8.0