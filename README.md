# node-red-contrib-redplc-piface

Node-Red node for PiFace Digital<br>

## Node Features
- 8 x Digital Outputs with 2 x Relays
- 8 x Digital Inputs with 4 tactile Switches
- 8 x Leds for Digital Inputs
- Four selectable Module Address 

[PiFace Digital more Info](http://www.piface.org.uk/products/piface_digital_2/)

## Install

For using with Ladder-Logic install
[redPlc](https://www.npmjs.com/package/node-red-contrib-redplc) nodes

For using with other nodes, install
[module](https://www.npmjs.com/package/node-red-contrib-redplc-module) nodes

Install with Node-Red Palette Manager or npm command:
```
cd ~/.node-red
npm install node-red-contrib-redplc-piface
```

## Usage
Update is triggered by redPlc cpu node<br>
or module-update node<br>
This node reads/writes from/to Node-Red global variables<br>
This node works only on Raspberry Pi with Raspberry Pi OS<br>
Enable SPI with raspi-config

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
