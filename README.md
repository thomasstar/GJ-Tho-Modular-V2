# GJ-Tho-Modular-V2
![overview](https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/overview.jpg)
GJ-Tho Modular V2 is a 3D printable rhythm game controller case for use with games like Beatmania IIDX, BMS or other. This is an updated model of the GJ-Tho Modular found on Thingiverse. This case is intended for use with arcade style push buttons.
# General info
Before you start printing, please note this is not a full guide on how to make a working controller. you still need the knowledge and resoruces to wire everything together, source your own PCB and firmware. This model also requires the use of other non 3d printable parts like couplers, rotary encoders, heat inserts and the tools to properly install it.
You can print the "heat_insert_test" part to make sure you have the correct size heat insert and 3d print settings. This might be a good idea to do before you start printing the parts.
Most parts if not all can be sourced from places like Aliexpress. I will try to keep the resource list updated with links.
# Parts
The case are assembled mainly by using m3 and m5 nuts and bolts. The m3 heat inserts are used for the panel parts and turntable assembly. It might be a good idea to have a bunch of m3 and m5 hex nuts for this project. and m3 screws in various lengths, but mostly 12mm m3 screws. When sourcing the parts, please follow the part lists. Do NOT use countersunk screws for this project.

For the case frame and side parts you will need the following:<br/>
8x M5 15mm screws<br/>
4x M5 80mm screws<br/>
12x M5 hex nuts<br/>
26x M3(OD4.2mm) heat inserts. about 5mm in length (maximum 10mm)<br/>
26x M3 12mm screws<br/>
4x adheasive rubber feet (about 5mm height) use whatever you prefer<br/>

Parts to print (case):<br/>
2x frame_a<br/>
2x frame_b<br/>
2x frame_center<br/>
2x side_center<br/>
1x side<br/>
1x side_usb<br/>
1x pcb-mount_leonardo OR 1x pcb-mount_pico (or none if you are planning to use something else)<br/>
1x panel_turntable<br/>
1x panel_buttons_2e OR 1x panel_buttons_4e (2e is two extra buttons, 4e is four. choose what you prefer)<br/>
2x panel_bottom
2x panel_center
![cad overview case](https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/cad%20overview%20labeled.jpg)

Parts you need for the turntable:<br/>
12x M3 12mm screws<br/>
4x m3 15mm screws<br/>
8x m3 hex nuts<br/>
1x m5 hex nut<br/>
4x M3(OD4.2mm) heat inserts. about 5mm in length (maximum 10mm)<br/>
1x Rotary encoder (refer to picture below)<br/>
1x coupler (refer to picture below)<br/>
1x ledstrip (optional if you want light) about 330mm length and maximum 12mm width<br/>
![Coupler and Encoder](https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/coupler_encoder.jpg)

Parts to print (turntable):<br/>
1x tt_center<br/>
1x tt_disc<br/>
1x tt_encoder-mount<br/>
1x tt_ledring<br/>
1x tt_led-cover<br/>
1x tt_spacer<br/>
1x tt_lock<br/>
1x tt_cutguide (optional part. you can use this as a guide when cutting turntable grip material. or print it in something like TPU to attach on top of the turntable disc)<br/>
![cad overview turntable](https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/cad%20overview%20turntable%20lebeled.jpg)
![cad overview tt parts](https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/cad%20overview%20tt%20parts%20labeled.png)

# Assembly
Let's start by assemble the case. First install the M3 heat insterts to the frame parts (optinally you can do this after the assembly too if you find that easier). Then put the frame and side parts together. Please follow the cad overview picture above as a guide. Place the M5 hex nuts in the sockets. Then tighten all the M5 screws together. for now do not tighten it all the way. leavy some room for small adjustement. I hightly reccomend doing this on a large flat surface.<br/>
If it's not too obious, this is the location of where to install the heatinserts:
![frame heatinsert location](https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/frame%20heatinsert%20location.jpg)
![frame center heatinsert location](https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/frame%20center%20heatinsert%20location.jpg)

Then install the panel_turntable and panel_buttons using m3 12mm screws. Once the top panels are installed, you can tighten the M5 screws.<br/>
When the frame and top panels are tighten, you can install the panel_bottom and panel_center parts, but it might be a good idea to do this as a final step in the whole build process.<br/>

Now the turntable. start by installing the tt_ledring to the panel_turntable (you can remove the panel from the case while assembling the turntable if you want).<br/>
Install the m3 heatinsterts to the tt_ledring and tt_center parts. I marked the location in this picture:
![tt heatinsert location](https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/tt%20heatinsert%20location.jpg)
Add ledstrip to the tt_ledcover (optional if you want turntable light).<br/>
Install the tt_ledcover to the panel using 4x M3 12mm screws and hex nuts. follow the cad overview picture above.<br/>
Now install the encoder to the tt_encoder-mount (you most likely got 3x screw when you bought the encoder. if not you need 3x M3 6mm screws). Install the encoder plate to the tt_center using 4x 12mm screws.<br/>
Install a M5 hex nut to the center of the tt_spacer and 4x M3 hex nuts to the tt_lock. The spacer part should be between the coupler and bottom of the turntable disc. The lock part may be optional. it will make it possible to remove the turntable disc after assembly.<br/>

Put the turntable disc, coupler, spacer and lock together using 4x 15mm M3 screws like shown: 
![tt disc install order](https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/irlpic_turntable10.jpg)
You can replace the stock screw on the coupler with something bigger to make it easy to access. but it is optional.<br/>

Now might be a good time to talk about friction. For now the disc will just spin freely. You got some options. easiest option is to simply put an oil seal bewteen the encoder and coupler. like shown here: 
![tt oilseal](https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/irlpic_turntable8.jpg)
Make sure it is at least 2mm thickness and enought inner diameter to sit around the encoder shaft. you may need to do some experimenting to find something that works for you.<br/>
Another option is to use felt pads. Felt pads can be installed on top of the tt_center part so it touches the bottom of the turntable disc. make sure it is at least 2mm thick.<br/>
In order for this to work, the turntable bottom must be smooth as possible. you can either sand it, or print the turntable disc on a smooth bed surface.<br/>

Install the disc to the encoder shaft. you may need a allen wrench tool to tighten the coupler to the encoder shaft. like shown in this image: https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/irlpic_turntable6.jpg<br/>
Start by having much friction, like you need much more more force to move the turntable than what you would prefer. DO NOT overtighten the coupler to the shaft.<br/>
We can now make som fine adjustements on the turntable friction. in order to this, use a M5 screw about 20mm in length. just make sure it is long enought to reach the top of the encoder shaft like shown in this image: https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/irlpic_turntable7.jpg<br/>
when you start tightening the screw, this will move the turntable disc further away from the oilseal or felt. by doing this you can find your perfect friction.<br/>
You can reset this process by loosening the coupler, and start all over again.<br/>
When you are satisfied with the result, double check the coupler and make sure the screw has not moved while adjusting. now remove the M5 screw you used for the adjusting.<br/>

Once you have the turntable assembled like shown below, you can install it to the panel using 4x M3 12mm screws.<br/>
![tt_assembled](https://github.com/thomasstar/GJ-Tho-Modular-V2/blob/main/pictures/irlpic_turntable4.jpg)
For more pictures of the turntable assembly, check the pictures folder.<br/>

Update: I've noticed some encoders have longer shafts. this will cause it to hit the m5 nut inside the tt_spacer part resulting in higher mount position. so only solution at the moment while I make some design changes, is to remove the m5 nut inside the tt_spacer part and install the disc without having the option to fine adjust the distance using the intended design metod. sorry!

This should cover most of the build process. The rest relies on you. You may refer to the Wiki link below for more useful information regarding parts, pcb and firmwares. Good luck!

# Resources
https://rhythm-cons.wiki/controllers/beatmania-iidx/beatmania-iidx/<br/>

I will add more stuff here later...<br/>

# Final notes
I wanna thank the Cons&Stuff community and all the people who build and shared feedback of my previous projects. This is the reason I'm doing this, and having fun while doing so!

