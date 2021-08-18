# Neotron Expansion Template

This repository contains a template PCB you can use as the start of a new Neotron Expansion Card design.

It contains an MCP23S17 SPI I/O expander, connected to the SPI bus. It also contains an I²C EEPROM connected to the I²C bus and the unique slot address lines. The I/O expander has eight LEDs and eight switches fitted.

There is a jumper which will allow you to program the EEPROM from your Neotron system. Normally this jumper is not fitted, making the EEPROM read-only. The contents of the EEPROM are TBD, but will describe the expansion card to the Neotron OS so that it can be auto-configured and any necessary drivers loaded.

## Using this template

To use this template, simply copy the files in this repository and edit away! You'll probably want to delete everything on the schematic except the edge connector and the EEPROM (unless you really need an SPI I/O exander...).

## Licence

This schematic and PCB design is Copyright (c) 2021 The Neotron Developers, et al.

[![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Contribution Agreement

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be licensed as above, without any additional terms or conditions.

