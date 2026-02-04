# aphelo30

![desk pic 1](https://github.com/MajinEvelyn/aphelo30/blob/main/img/shot%204.JPG)
![desk pic 2](https://github.com/MajinEvelyn/aphelo30/blob/main/img/shot%208%20cropped.JPG)

Pictured with Chicago Steno keycaps by [Asymplex](https://www.asymplex.xyz/), case printed in Cream PETG-HF.

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

![bottom case](https://github.com/MajinEvelyn/aphelo30/blob/main/img/bottom%20case.JPG)

## Carrying Case

I designed this to slide in both halves vertically, with the USB ports facing up and open air to protect the keycaps. It is not fully enclosed because for my use case I am placing it in a bag. I glued some felt to the bottom of the case to cushion it, and ribbons to make pulling the keeb halves out easy.

![carry case](https://github.com/MajinEvelyn/aphelo30/blob/main/img/carry%20case.JPG)

## Firmware
ZMK: https://github.com/MajinEvelyn/zmk-config-aphelo30

## BOM

| Name | Count | Notes |
| ---- | ----- | ---------- |
| PCB | 2 | These are reversible, so either PCB works with either half. |
| Nice! Nano v2 MCU | 2 | |
| Choc v1 Switches | 30 | |
| Choc v1 Hotswap Sockets | 30 | |
| Choc v1 Keycaps | 30 | |
| Power Switch | 2 | |
| Reset Switch | 2 | You can omit these if you are fine with using ZMK reset behavior or shorting RST pins to reflash firmware. |
| 110mah LiPo Battery | 2 | There is plenty of space for other batteries inside the case, but I have not tested others. |
| Bumpons | 8 | Size is up to your preference. |
| M2(x8mm) Screws | 8 | Countersunk screws are best, they will seat perfectly into the chamfered holes in the bottom case. |
| M2 Heat Set Inserts | 8 | |
