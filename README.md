SPI-Py: Hardware SPI as a C Extension for Python
======

COPYRIGHT (C) 2012 Louis Thiery. All rights reserved. Further work by Connor Wolf.

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License V2 as published by the Free Software Foundation.

LIABILITY  
This program is distributed for educational purposes only and is no way suitable for any particular application,
especially commercial. There is no implied suitability so use at your own risk!

This fork of SPI-Py made to change the line cs_change to 0 not 1 in spi.c to allow the RC522 RFID tag readers to work correctly. This issue is described here: https://github.com/raspberrypi/linux/issues/1547 

# Installation

```
$ git clone https://github.com/simonmonk/SPI-Py.git
$ cd SPI-Py
$ sudo python setup.py install
```
