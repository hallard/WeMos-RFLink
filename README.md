RFLink ESP8266 WeMos Shield
============================

This shield is used to hold [RFLink][4] Software with WeMos ESP8266 boards it has just few minimal features.
- I2C Pullups placement
- Classic I2C 128x64 OLED connector
- Placement for Aurel RF transceiver [RTX-MID-3V][5] module
- Placement for choosing single Wire, SMA or u-FL Antenna type
- WS2812B Type LED for visual indication

You can find more information on WeMos on their [site][1], it's really well documented.
I now use WeMos boards instead of NodeMCU's one because they're just smaller, features remains the same, but I also suspect WeMos regulator far better quality than the one used on NodeMCU that are just fake of originals AMS117 3V3.

**Boards are ordered as testing from OSHPark, I did not fully tested them yet, I will update as soon has I got them in my hands. Use at your own risks**

Detailed Description
====================

Look at the schematics for more informations.

### Schematic  
![schematic](https://raw.githubusercontent.com/hallard/WeMos-RFLink/master/WeMos-RFLink-sch.png)  

### Boards  
<img src="https://raw.githubusercontent.com/hallard/WeMos-RFLink/master/WeMos-RFLink-top.png" alt="Top" width="40%" height="40%">&nbsp;
<img src="https://raw.githubusercontent.com/hallard/WeMos-RFLink/master/WeMos-RFLink-bot.png" alt="Bottom" width="40%" height="40%">&nbsp; 

You can order the PCB of this board v1.0 at [OSHPARK][3]

### Assembled boards

I'm currently waiting for boards from OSHPARK

##License WeMos-RFLink

You can do whatever you like with this design.

##Misc
See news and other projects on my [blog][2] 
 
[1]: http://www.wemos.cc/wiki/doku.php?id=en:d1_mini
[2]: https://hallard.me
[3]: https://oshpark.com/shared_projects/KuYqTIB7
[4]: https://sourceforge.net/projects/rflink/
[5]: http://www.tme.eu/gb/details/rtx-mid-3v/aurel-rf-communication-modules/aurel/650201033g/

