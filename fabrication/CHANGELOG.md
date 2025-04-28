Version 1.2:
* R26 100k -> 87k6
* R27 100k -> 110k
* C21 4.7uF -> 10uF
* C26 4.7uF -> 10uF
* Add C19, C20 in parrallel with C21, C26 for example 22uF/35V -> C3216X5R1V226M160AC -> mouser 810-c3216x5r1v226m
* Add vias next to SO8 to transfer heat faster to backside
* Use MLX81339 NC pins for routing GND
* R15, R16 100R -> 10R
* D18, D19 DESD5V0S1BA-7
* D17, D16 D20V0L1B2WS-7 -> ESD5Z24
* 2A increase track with to .8mm
* Increase fiducial size

Version 1.3:
* Update: ESP to ESP32-S3-WROOM-1-N16R8
* Add: optional 2k2 pull up on IO7 for debug purposes
