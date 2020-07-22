# WattsUp Meter Logger

## Installation

Tested on Ubuntu

1. create a virtual python3 environment: `virtualenv .env -p python3.7`, then activate it: `source .env/bin/activate`
2. `pip install pyserial numpy matplotlib`
3. plug in the usb to your computer, then `sudo chown $USER /dev/ttyUSB0`

## Usage

1. log power: `python wattsup.py -l -o sample.log`

2. plot power and energy (needs to `pip install PyQt5`): `python plot.py sample.log sample.png`
