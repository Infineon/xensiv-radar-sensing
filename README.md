# RadarSensing Library

## Overview

This library provides APIs to interface with the RadarSensing library that allows user to use existing radar applications such as presence detection, entrance counter or build applications on top.

## Features

- Ability to use existing radar applications: presence detection, entrance counter.
- Availability of APIs to configure parameters for presence detection (range, sensitivity) and entrance counter (orientation, installation, entrance width and more) applications

## Requirements

- [ModusToolbox® software](https://www.cypress.com/products/modustoolbox-software-environment) v2.2

    **Note:** This code example version requires ModusToolbox software version 2.2 or later and is not backward compatible with v2.1 or older versions.
- Board Support Package (BSP) minimum required version: 2.0.0
- Programming Language: C
- Associated Parts: All [PSoC® 6 MCU](http://www.cypress.com/PSoC6) parts

## Supported Toolchains (make variable 'TOOLCHAIN')

- GNU Arm® Embedded Compiler v9.3.1 (`GCC_ARM`) - Default value of `TOOLCHAIN`

## Supported Kits (make variable 'TARGET')

- Rapid IoT Connect Developer Kit (`CYSBSYSKIT-DEV-01`)

## Hardware Setup

This code example requires the XENSIV™ BGT60TR13C Radar Wing Board as part of the Connected Sensor Kit.

1. Connect Radar Wing Board to `CYSBSYSKIT-DEV-01` kit with the pin headers.
2. Connect `CYSBSYSKIT-DEV-01` kit to PC with USB cable.
3. Place the `CYSBSYSKIT-DEV-01` kit at a location such as side of a door or ceiling of a door.

## Software Setup

### Quick Start

**Note:** Please refer to the RadarSensing library API documentation for details.

### More information

- [Connected Sensor Kit](https://www.infineon.com/connectedsensorkit)
- [CYSBSYSKIT-DEV-01](https://github.com/cypresssemiconductorco/TARGET_CYSBSYSKIT-DEV-01)
- [API Reference Guide](https://cypresssemiconductorco.github.io/xensiv-radar-sensing/radarsensing_api_reference_manual/html/index.html)
- [Infineon Radar Sensors](https://www.infineon.com/cms/en/product/sensor/radar-sensors)
- [ModusToolbox](https://www.cypress.com/products/modustoolbox-software-environment)
- [PSoC 6 Code Examples using ModusToolbox IDE](https://github.com/cypresssemiconductorco/Code-Examples-for-ModusToolbox-Software)
- [PSoC 6 Resources](https://community.cypress.com/)

---
© Infineon Semiconductors, 2019-2021.
