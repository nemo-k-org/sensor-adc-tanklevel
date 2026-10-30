# Nemo-K tank level sensor using ADS1115 A/D-converter chip

## Overview

This is Nemo-K board for ESP-01 and ADS1115 (ADS1115IDGSR) A/D-convert chip. The purpose of this sensor
is to read regular tank sensors (senders) giving N-M ohm resistance based on the tank level.

The board sends tank level information to Signal K server.

The board is designed to be used with ESP-01 microcontroller running Nemo-K firmware.

To build you need
 * The PCB
 * ESP-01S

## Content

The repository contains schematics and PCB in KiCad 10.0 format. The footprint properties contains LCSC part numbers
used by [JLCPBC.com](https://jlcpcb.com). If present, the `sensor-sensor-adc-tanklevel/production/` contains all
necessary files to order boards from JLCPCB. The production files can be easily re-created using
[KiCad Fabrication Toolkit](https://github.com/bennymeg/Fabrication-Toolkit).

The Nemo-K project is not affiliated or sponsored by JLCPCB. The project does not endorse JLCPCB.

## Changelog

2026-10-23

## Copyright and License

The license and copyright can be found in the file `LICENSE`.

The license and copyright cover only the schematic diagram and the PCB design. It does not cover footprints and other
embedded elements or technical documentation which may or may not be covered by their own licenses.
