# Vita 1000 3G Wireless charging mod
# [Vita Wireless Charging mod video](https://www.youtube.com/embed/Zvf_ijJDTGA)
------

![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/IMG_5631.JPG)

Tools:
------
Soldering iron

Wire cutters

Screwdriver

dremel (optional)

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

This alternate [Qi reciever](https://www.amazon.com/Bewinner-Standard-Wireless-Charger-Receiver/dp/B07M6CRQ71) will need to be solderd to the TP4056 board. Allowing you to do the hard mod or it would allow you to use the usb port as an extra charging port with a shell modifaction.

![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/images4.png)

# Charging 
----

Estimated charging time: 2.5 to 3 hours
---
The Vita Battery is 3.7V 2210 mAh. So 2210 at a charge rate of 1 A it should charge in about 2 hours 39 minutes to 3 hours and 6 minutes depending the Efficiency loss of the battery. The TP4056 will show red/orange light when charging and a green light when the battery is charged.

Notes:
The vita charging light will not come on in the simple mod, the battery indacator takes 3 minutes or more to update sometimes. This seems to be when the vita checks the batteries charge.

# Heat
----

It does get hot, thats why I chose to put the coil over grip and under the right speaker. The speaker clip plastic keeps the coil in place and the location keeps it as far away from the back touch pad as possible. It gets hot but will cool rapidly.

# Installation

Preping the rear Vita shell
-----
You will need to remove some of the plastic on the inside of the the vita shell. leave a little bit for the battery to latch under, but use your wire cutters or dremal to clear out the areas in red. Becareful of the touch pad connector. 

![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/IMG_5663.PNG)

Trim off excess paper on the Qi reciever. Be mindfull there is flex chip and a coil in there see the alternate Qi reciever picture above for referance. do a test fit.

![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/IMG_5664.PNG)

It should look like this when all said and done with the battery. Test that you get a charging light when you put it on the charging dock. 

![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/IMG_5631.JPG)

Now you have some options on wiring there is a simple mod that i did and the harder mod. 

Wiring diagram for the TP4056 BPB 
![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/IMG_5659.PNG)

Simple mod:
---
Just cut red positve and blacvk grornd wires on the vita battery using the wiring diagram above. Do not cut the white wire. The half of the wires that connect to the battary side need to be solderd to the B+ and B- pads. The red wire to the B+ pad and the black wire to the B- pad on the TP4056 board. The wires to the connecter to the vita mainboard needs to be soldered to thw out+ and teh out- solder the red positive wire to the out+ pad on teh TP4056 board and the black ground to teh out-. marked V+ and V- on the diagram above.

If you use a Qi reciever that will need to be soldered, solder the wires to the usb side of the TP4056 borad. Red positive to + pad and black negitive ro the - pad on the usb side of the TP4056 board.

pros/cons
---
Keeps charging on the back side of the shell and no wires from the front shell to the back shell

Weird battery dection after charging takes several minutes for the vita to detect the new charge level. After that it works normally.


Hard Mod:
--
I have not done this one yet.

Sloder the Qut+ and Out- from TP4056 (or even the positive and negitive of a Qi recever 5v 1a) right to the usb positive of the vita main board. 

pros/cons
---
Will activate the vita charging light
Better battery detection and charging.

You'll have to solder to the main board of the Vita.

Wiring diagram for the Vita Main board
![image](https://github.com/CrashCortez/Vita-Wireless-Charging-mod/blob/main/img_5679.png)
