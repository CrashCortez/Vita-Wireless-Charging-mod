# Vita Wireless Charging mod
Vita Wireless Charging mod tutorial

![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/IMG_5631.JPG)

# Vita 1000 3G Wireless charging mod
--------

Tools:
------
Soldering iron

Wire cutters

Screwdriver

Dermal (optional)

Parts: 
--------

TP4056 5V 1A Lithium Battery Charging and Protection Board

![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/images3.jpg)

Qi Wireless Fast Charger Dock Charging Pad + Receiver

![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/images.png)

![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/images2.jpg)

A TP4056 5V 1A Lithium Battery Charging and Protection Board is used in this mod there are 2 tpyes that could be used. I used the [Mirco USB](https://www.ebay.com/itm/2pcs-5V-1A-Micro-USB-18650-Lithium-Battery-TP4056-Charging-Board-Charger-Module/191850083395) version, you could also use the  [USB Type-C](https://www.ebay.com/itm/163448894634) version. Also note if you get Qi reciever that can be soldered to the TP4056 you could free up the usb port and use it as an external charing port upgrade. with further shell modifacations.


I used the type A micro usb [Qi Wireless Fast Charger Dock Charging Pad + Receiver](https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2047675.m570.l1313&_nkw=Qi+Wireless+Fast+Charger+Dock+Charging+Pad+%2B+Receiver+&_sacat=0)

As well as soldering supplies and wires.

# Charging 
----

Estimated charging time: 2.5 to 3 hours
---
The Vita Battery 2210 mAh. 2210 at a charge rate of 1 A it should charge to max with an Efficiency loss of 20% in about 2 hours 39 minutes.  Or at 40% EL in about 3 hours and 6 minutes. The TP4056 will show red/orange light when charging and a green light when the battery is charged.

Notes:
The vita charging light will not come on in the simple mod, the battery indacator takes 3 minutes or to update sometimes. This seems to be when the vita checks the batteries charge.

# Installation

Wiring diagram for the TP4056 BPB 
![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/IMG_5659.PNG)

Simple mod:
---
Just cut red positve and blacvk grornd wires on the vita battery using the wiring diagram above. The half of the wires that connect to the battary side need to be solderd to the B+ and B- pads. The red wire to the B+ pad and the black wire to the B- pad on the TP4056 board. The wires to the connecter to the vita mainboard needs to be soldered to thw out+ and teh out- solder the red positive wire to the out+ pad on teh TP4056 board and the black ground to teh out-. marked V+ and V- on the diagram above.

If you use a Qi reciever that will need to be soldered, solder the wires to the usb side of the TP4056 borad. Red positive to + pad and black negitive ro the - pad on the usb side of the TP4056 board.

pros/cons
---
Keeps charging on the back side of the shell and no wires from the front shell to the back shell

Weird battery dection after charging takes several minutes for the vita to detect the new charge level. After that it works normally.


Hard Mod:
I have not done this one yet.

Sloder the Qut+ and Out- from TP4056 (or even the positive and negitive of a Qi recever 5v 1a) right to the usb positive of the vita main board. 

pros/cons
---
Will activate the vita charging light
Better battery detection and charging.

You'll have to solder to the main board of the Vita.
