# RadarSensing Library Release Notes

This library provides APIs to interface with the RadarSensing library that allows user to use existing radar applications such as presence detection, entrance counter or build applications on top.

### What's Included?

* APIs to initialize/de-initialize the RadarSensing Library.
* APIs to configure and use existing radar applications such as presence detection, entrance counter.

#### v1.1.0

* Use Hardware Abstraction Layer (mtb-hal-cat1) 2.x.
* Added support for IAR and ARM compilers.

#### v1.0.0

* Allow user define own memory allocation scheme
* Update presence detection algorithm

#### v0.5.0

* Initial release

### Known Issues

* To use the maximum supported SPI frequency of 25MHz, user might need to increase compiler optmization level

### Supported Software and Tools

This version of the RadarSensing Library was validated for compatibility with the following Software and Tools:

| Software and Tools                        | Version |
| :---                                      | :----:  |
| ModusToolbox Software Environment         | 2.4     |
| CAT1 Hardware Abstraction Layers          | 2.0.0   |
| GCC Compiler                              | 10.3.1  |
| IAR Compiler                              | 8.42    |
| ARM Compiler 6                            | 6.13    |

Minimum required ModusToolbox Software Environment: v2.2

### More information

* [API Reference Guide](https://infineon.github.io/xensiv-radar-sensing/radarsensing_api_reference_manual/html/index.html)
* [Infineon Technologies](https://www.infineon.com)
* [Infineon GitHub](https://github.com/infineon)
* [ModusToolbox](https://www.cypress.com/products/modustoolbox-software-environment)
* [PSoC™ 6 Code Examples using ModusToolbox™ IDE](https://github.com/infineon/Code-Examples-for-ModusToolbox-Software)
* [ModusToolbox™ Software](https://github.com/Infineon/modustoolbox-software)
* [PSoC™ 6 Resources - KBA223067](https://community.cypress.com/docs/DOC-14644)

---
© Infineon Technologies Corporation, 2019-2022.
