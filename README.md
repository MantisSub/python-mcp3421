
# MCP3425

## Introduction

This is a Python3 library for the MCP3421 Analog to Digital Converter. The MCP3421 is a 1-Channel 
Analog to Digital Converter with I2C interface and 12-18 bit resolution
https://www.microchip.com/wwwproducts/en/MCP3421

The MCP3421 has the same footprint and electrical characteristics as the MCP3425.
This library configures the MCP3421 with 16 bit resolution so it can be used as a drop-in 
replacement for the MCP3425.


## Requirements

Download and install smbus2 library. Steps to install smbus are provided at:
https://pypi.org/project/smbus2/

```
pip3 install smbus2
```

## Installation

MCP3425 is pure Python 3 code and requires no compilation. Installation is easy:

```
python3 setup.py install
```
