# node-red-contrib-redplc-piface

redPlc module node for PiFace Digital.<br>

## Install

[redPlc use this module node. Install redPlc.](https://www.npmjs.com/package/node-red-contrib-redplc)

Install with Node-Red Palette Manager or npm command:
```
cd ~/.node-red
npm install node-red-contrib-redplc-piface
```

[PiFace Digital more Info](http://www.piface.org.uk/products/piface_digital_2/)

## Usage

Wire this node to first output of redPlc cpu node.<br>
Global variable I are updated with digital inputs.<br>
Global variable Q sets digital output and relays.<br>
This node works only on Raspberry Pi with Raspberry Pi OS.<br>
Enable SPI with raspi-config.

## I/O Mapping
### Digital Input (Variable I):
|Pin|Bit|Function|
|:--|:-:|:-------|
|I0|0|Input 0, Switch S0|
|I1|1|Input 1, Switch S1|
|I2|2|Input 2, Switch S2|
|I3|3|Input 3, Switch S3|
|I4|4|Input 4|
|I5|5|Input 5|
|I6|6|Input 6|
|I7|7|Input 7|

### Digital Output (Variable Q):
|Pin|Bit|Function|
|:--|:-:|:-------|
|O0|0|Output 0, Relay 0|
|O1|1|Output 1, Relay 1|
|O2|2|Output 2|
|O3|3|Output 3|
|O4|4|Output 4|
|O5|5|Output 5|
|O6|6|Output 6|
|O7|7|Output 7|

## Donate
If you like my work please support it with donate:

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ZDRCZBQFWV3A6)
