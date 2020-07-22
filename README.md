# WattsUp Meter Logger

## Installation

Tested on Ubuntu

1. create a virtual python3 environment: `virtualenv .env -p python3.7`
2. `pip install pyserial numpy matplotlib`
3. plug in the usb to your computer, then `sudo chown $USER /dev/ttyUSB0`

## Usage

`python wattsup.py -l -o sample.log`
