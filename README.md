<picture>
  <source media="(prefers-color-scheme: dark)" srcset="http://svg.wiersma.co.za/github/project.v2?title=sentinel&tag=presence%20detection&mode=dark">
  <source media="(prefers-color-scheme: light)" srcset="http://svg.wiersma.co.za/github/project.v2?title=sentinel&tag=presence%20detection">
  <img alt="Logo" src="http://svg.wiersma.co.za/github/project.v2?title=sentinel&tag=presence%20detection">
</picture>

[![GitHub release](https://img.shields.io/github/release/nrwiersma/sentinel.svg)](https://github.com/nrwiersma/sentinel/releases)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/nrwiersma/sentinel/main/LICENSE)

`Sentinal` is a presence detection device that uses a mmWave to detect occupancy. It can be used to control lights, fans, 
or other devices based on occupancy. It also include a light sensor to detect ambient light levels as well as a temperature 
and humidity sensor.

![board image](assets/assembled.png)

## Key Features

* Presence detection using LD2450 mmWave radar
* Ambient light detection using BH1750 light sensor
* Temperature and humidity detection using SHTC3 sensor
* RGB LED for status indication
* Native alarm integration

## Firmware

ESPHome firmware is available for the device. See the releases for the latest version. The firmware can be flashed 
using the [ESPHome Web installer](https://web.esphome.io).

## Hardware

The hardware is based on the ESP32-C3 module and the LD2450 mmWave radar module. The device is designed to be low power 
and can be powered using a 12v power supply, which is fairly common in home alarm systems.

See the [Schematic](/blob/main/hardware/schematic.pdf) for more details on the hardware design.

### BOM

See the [Interactive BOM](https://htmlpreview.github.io/?https://github.com/nrwiersma/sentinel/blob/main/bom/ibom.html) [(provided by InteractiveHtmlBom)
](https://github.com/openscopeproject/InteractiveHtmlBom).
