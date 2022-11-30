# pi-pwr: Power management script for Raspberry Pi

This script allows for various functions of a Raspberry Pi to be turned off to reduce overall power consumption.

## Installing this package
`wget -O - https://github.com/wildlife-systems/pi-pwr/raw/master/install | sudo bash`

## Usage
`pi-pwr <on|off>  <usb|wifi|bluetooth|hdmi|pwrled|actled>...`

e.g.

`pi-pwr off pwrled actled`

## Compatability
The following board revisions have been tested.

|Model|Revision|Notes|
|---|---|---|
|Raspberry Pi Model B Rev 2|000d<br>000e|Power LED cannot be software controlled.|
|Raspberry Pi Model B+|0013||
|Raspberry Pi 3 Model B|a02082||
|Raspberry Pi 3 Model B+||
|Raspberry Pi Zero W|9000c1||
|Raspberry Pi 4 Model B 4GB|c03111||

## Development
* Development of this script was done as part of the Levehulme Trust funded Automated Acoustic Observatories project at the University of York.
* Support for further devices was added as part of the Urban Nature Project at the Natural History Museum, London.
