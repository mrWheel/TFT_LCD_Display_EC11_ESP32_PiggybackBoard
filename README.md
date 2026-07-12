# TFT_LCD_Display_EC11 ESP32 PiggyBack Board

A universal ESP32 development board designed specifically for the popular **TFT_LCD_Display_EC11** display module.

The PiggyBack Board transforms the TFT_LCD_Display_EC11 into a complete and easy-to-use embedded development 
platform. Simply plug the display module into the PiggyBack Board, program the ESP32 through USB-C, and start 
building your application.

Whether you are creating an Internet radio, a smart home dashboard, a data logger or a music project, the
hardware is already taken care of.

---

## Why this Board?

The original TFT_LCD_Display_EC11 is a nice display module featuring:

- 2.4" TFT color display
- Rotary encoder
- Encoder push button
- Additional push button

Unfortunately, using the module directly requires many external connections and additional hardware.

The PiggyBack Board integrates everything needed to turn the display into a practical development platform.

---

## Features

- ESP32-S3 module
- USB-C programming and power
- 3.3V voltage regulator
- I²C expansion connector
- Universal GPIO expansion connector with 10 free pins
- Compatible with the TFT_LCD_Display_EC11 display module (only 2.4" version)
- Designed for easy hand assembly
- Fully open-source KiCad project

---

## Typical Applications

The board is intentionally application-independent.

Possible applications include:

- Internet Radio
- Smart Home Dashboard
- ESPHome Display
- Home Assistant Dashboard
- Audio Spectrum Analyzer
- Universal Timer
- MIDI Controller
- Industrial Control Panel
- Weather Station
- Music Instruments
- Data Logger

---

## Repository Contents

```text
Hardware/
    KiCad project
    Schematics
    PCB layout
    Gerber files

assets/
    Build instructions (future)
    Images
    Pinout

Examples/
    Example firmware (future)

openSCAD/
    Boxes to accommodate the Display, knobs and Piggyback Board

LICENSE
README.md
```

---

## Hardware Overview

The PiggyBack Board combines:

- ESP32-S3
- USB-C connector
- 3.3V regulator
- Expansion connectors
- TFT_LCD_Display_EC11 connector

The result is a compact standalone ESP32 platform requiring no additional wiring.

---

## Expansion Connectors

The board exposes:

### I²C Connector

- SDA
- SCL
- 3.3V
- GND

Ideal for sensors and external modules.

### Available GPIOs

| Software Pin Name | GPIO | Description |
|-------------------|----:|-------------|
| PIN_SPARE1 | 7 | General-purpose I/O |
| PIN_SPARE3 | 42 | General-purpose I/O |
| PIN_SPARE4 | 43 | General-purpose I/O |
| PIN_SPARE5 | 44 | General-purpose I/O |
| PIN_SPARE6 | 47 | General-purpose I/O |
| PIN_SPARE7 | 48 | General-purpose I/O |

- 3.3V
- 5volt (in/out)
- GND

---

## Software

The board is compatible with:

- Arduino IDE
- PlatformIO
- ESP-IDF

No special libraries are required beyond those needed for your own application.

---

## Designed for Makers

One of the design goals was ease of assembly.
All components were selected to be hand solderable whenever practical.
Revision 3 added a Micro SD slot.

---

## Assets

Various images, the schematic as PDF and a Bill Off Material

## Github Pages

Complete project documentation, build instructions and photographs are available here:

---

## License

This project is released as Open Source.

See the LICENSE file for details.

---

## Acknowledgements

This project was inspired by the popular TFT_LCD_Display_EC11 display module and by the philosophy behind the 
well-known "Cheap Yellow Display" (CYD): providing makers with a compact hardware platform so they can focus on 
developing their application instead of designing the supporting electronics.
