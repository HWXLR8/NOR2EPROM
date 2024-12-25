# NOR2EPROM
This is a "simple" drop in replacement for 27C322 UV EPROMs which uses an MX29LV320 (or pin-compatible) NOR flash.
Address lines are shifted from 5V -> 3.3V using 3x 74LVC245 and data lines are shifted from 3.3V -> 5V using 2x 74HCT245.

### Schematic
<img src="pics/schematic.png">

### PCB
<p float="left">
<img src="pics/pcb-front.png" width="200px">
<img src="pics/pcb-back.png" width="203px">
<img src="pics/pcbnew.png" width="207px">
</p>
