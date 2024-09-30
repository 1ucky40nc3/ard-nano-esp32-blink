# Arduino Nano ESP32 - Blink

How to flash the `Blink` example to an [Arduino Nano ESP32] using the [Arduino IDE].

## Requirements

(This tutorial is under the assumption that you use a Linux machine.)

- [Arduino IDE] (version 2.3.3)
- [Arduino Nano ESP32]

## Getting Started

Please execute the following steps:

- Connect the Arduino Nano ESP32 to your PC using a USB-C cable
- Follow the [Getting Started with Nano ESP32] to setup your environment
- Select the `Blink` example in the IDE through `File > Examples > 01. Basis > Blink`
- Select the *board*  through `Tools > Board > Arduino ESP32 Boards > Arduino Nano ESP32`
- Select the *port* through `Tools > Port > ttyACM0`
- Select the *USB mode* through `Tools > USB Mode > Debug Mode (Hardware CDC)`
- Select the *programmer*  through `Tools > Programmer > Esptool`
- Upload the sketch through `Sketch > Upload Using Programmer`

## Sources

- [Arduino IDE]
- [Arduino Nano ESP32]
- [Getting Started with Nano ESP32]

[Arduino IDE]: https://www.arduino.cc/en/software
[Arduino Nano ESP32]: https://docs.arduino.cc/hardware/nano-esp32/
[Getting Started with Nano ESP32]: https://docs.arduino.cc/tutorials/nano-esp32/getting-started-nano-esp32/