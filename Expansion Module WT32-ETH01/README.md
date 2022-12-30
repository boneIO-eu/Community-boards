# boneIO module expander WT32-ETH01

This software script allows you to use the ESP32 + RS485 transceiver to interact with relay boards to boneIO.

It provides all known information via MQTT.

This allows you to integrate the device with Home Assistant.

You can find the configuration YAML files in the `yaml` folder.

## Foto
![foto1](docs/foto1.jpg?raw=true "boneio expander1")
![foto2](docs/foto2.jpg?raw=true "boneio expander2")
## Pinout
1. 
Power input
24 DC power supply

2.
RS485
TX 				- GPIO1
RX 				- GPIO3
Flow Control  	- GPIO4

3. 
USB
USB-C is for uploading software

4.
WT32-ETH01
ESP32 controller right with Ethernet for MQTT communication

5.
INPUTS
Digital inputs controlled by low state
IN1 - GPIO39
IN2 - GPIO36
IN3 - GPIO15
IN4 - GPIO14
IN5 - GPIO35
IN6 - GPIO17

6.
I2C
SDA - GPIO32
SCL - GPIO33
Frequency - 100kHz

7.
1-WIRE
DATA - GPIO5

Exit and input description:
![foto3](docs/foto2.png?raw=true "boneio expander3")


