---
permalink: /index.html
layout: single
---

# basic DC mixer

Basic DC mixer with 4 ins and one out.

DC coupled, can work with both audio and CV.

Mute switches and vol pots on all voices.

One main out and one inverted out.

You'll find the schematic of this module below: 

![basic dc Mixer schematic](Documentation/image/Basic-DC-mixer-schematic.svg)

Regular build, I use ceramic capacitors but you can use film/polyester.

:warning: When building modules, always do it in this order (from smallest component to highest):
- diodes
- resistors
- DIP chips
- capacitors (film/ceramic)
- Electrolytic capacitors

For the next part, always place them without soldering them on: 
- jacks, pots and switches that go thought the front panel

Once placed, put in place the front panel, then fasten all components to it. Once this is done, you can solder them. 

![3D Basic-DC-mixer(front)](Documentation/image/Basic-DC-mixer-3D_top.png)

![3D Basic-DC-mixer(back)](Documentation/image/Basic-DC-mixer-3D_bottom.png)

![3D Basic-DC-mixer(iso)](Documentation/image/Basic-DC-mixer-3D_top30deg.png)

[See bom globale](Documentation/BoM/Basic-DC-mixer-ibom-global.html)

[See bom board jack](Documentation/BoM/Basic-DC-mixer-ibom-jack.html)
