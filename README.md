# aphelo30

![desk pic](https://github.com/MajinEvelyn/aphelo30/blob/main/img/aphelo%20desk.jpg)

## Design Parameters
- Full split
- ZMK powered BLE wireless
- Nice! Nano v2 controlled
- Reversible PCB
- 30 keys in 3x5 configuration
- Choc v1 Switches with hotswap sockets
- No thumb keys
- Aggressive splay

![scrub jay](https://github.com/MajinEvelyn/aphelo30/blob/main/img/scrub%20jay.jpg)

Named for the *Aphelocoma* genus of scrub jay birds. 

## Overview

This weird combination of features is designed for my hands, which no currently existing boards accommodate. I have RSI issues in both of my thumbs, to the point that even single thumb key layouts don't work for me. Aside from this, the aggressive splay and finger positions were made with Ergopad, and recreated in Ergogen. 

In this repo you will find all files related to the design process, including the Ergogen config, KiCAD PCB files, related Gerbers, and case 3d files for printing. Unfortunately, I was only able to get the PCB to a 115x85mm footprint with this splay, so a little outside of the <100x100mm discount size for JLCPCB. Despite this and the expensive microcontroller, you should be able to build this board for somewhere between 80-120$.

## Case

There are 4 bosses for heat set inserts on the underside of each half's top case. Press them into each boss with a soldering iron, and use your M2 screws through the holes in the bottom case to screw into the heat set inserts.
There are heat set insert soldering tips available for pretty cheap to make this process easy, but I've heard this is easy enough with typical soldering iron tips.

## Firmware
ZMK: https://github.com/MajinEvelyn/zmk-config-aphelo30

## BOM

| Name | Count | Notes |
| ---- | ----- | ---------- |
| PCB | 2 | |
| Nice! Nano v2 MCU | 2 | |
| Choc v1 Switches | 30 | |
| Choc v1 Hotswap Sockets | 30 | |
| Choc v1 Keycaps | 30 | |
| Power Switch | 2 | |
| Reset Switch (optional) | 2 | |
| 110mah LiPo Battery | 2 | |
| Bumpons | 8 | |
| M2(x8) Screws (countersunk) | 8 | |
| M2 Heat Set Inserts | 8 | |
