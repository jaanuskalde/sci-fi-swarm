sci-fi-swarm
============

All PCBs 0.6mm thick. Donno where to get power.

High level board
----------------
Something awesome to do picture processing

Middle section
--------------

###Battery###
Capacity : 240mAh
Voltage : 3.7v
Size : 30mm x 19.5mm x 5.5mm
Weight : 5.4g

###Front PCB###
SEN-08667 from sparkfun
6x6x4.5mm
laser maybe?

###Top PCB###
2335787 - RGB led
1779478 - ceramic antenna

###Back PCB###
Film solar cell 12.7 x 64mm

Low level board
---------------
Radio communication, motor control, battery charging
Thickness: 1mm components + 0.6mm PCB + 0.5mm components

###BOM###
|Component| Code | Details
|---|---|---
|ATMEGA128RFA1 | 1841596 | 7.36€
|32kHz crystal | 1712821 |
|16MHz crystal | 1842186 |
|2.4GHz Balun | 1885504 |
|mosfet|2311188| DFN2020
|capacitor||X7R 4V 0805
|capacitor||X7R 4V 0402
|Magnet sensors|
|Switching regulator|1816333|3MHz, 2.5V, 600mA, integrated inductor
|SPV1040 MPPT|511-SPV1040T|
|10u inductor|2287374|2x2x1mm
