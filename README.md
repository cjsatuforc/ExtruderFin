ExtruderFin
===========

A Kinen Fin to add support for 3D printer Extuder and Heated bed to a Kinen compatible TinyG board. This project is a redesign
of the first Kinen fin for temperature control on the kinen platform found here https://github.com/Kinen/TempFin1 . This redesign
transitions the platform away from the Atmel 328p to A FreeScale ARM Cortex M0+ for more performane per dollar. The system wide 
reset is now jumperable so that the fin and the motherboard can be programmed/reset independently of eachother.

To lear more about TinyG and Kinen visit the links below:

https://github.com/synthetos/TinyG
https://github.com/kinen/kinen/wiki

Specs
- FreeScale MKL05Z32VLF4 ARM Cortex M0+ 48MHZ
- Texas Instruments DRV8825 Integrated Stepper Driver
- 3 FDT439N MOSFETs for hotend and two fans
- Maxim Integrated MAX31855EASA+ Thermocouple amplifier
- Two Thermistor channels with shared reference circuit (allows for redundant thermistors instead of a single thermocouple)
- 24VDC System
- ARM Cortex M JTAG port supporting serial wire debugging
- FTDI cable/adapter port for serial firmware loading
- Compatible with the previous Kinen specification and the recently updated specifiation.

![Prototype 1](/V1.2%20Final.png)


Recently Fabricated Prototype! 6/17/14
![Fabricated Prototype](/IMG_1627.JPG)
