Additional files to print, which are really useful:

## mechanical
[Keyed XZ bearing blocks](https://github.com/hymness1/Switchwire_Things/tree/main/Z_bearing_blocks_keyed) which restrict the movement of your gantry during leveling.  


## electronics
LDO WAGO mount: https://github.com/MotorDynamicsLab/LDOVoronSW/blob/main/STLs/wago_221-413_3x3_vertical_mount.stl
other WAGO mount: https://www.printables.com/model/150807-voron-24-wago-221-415-mount

## toolhead

## Z probe
If you want to use the Klicky mod, the [Unklicky](https://github.com/majarspeed/Unklicky) mod is recommended. The BOM Switchwire doesn't have a rigid bed structure and it runs on only one rail. This makes Unklicky the most suitable because it needs the lowest actuation force (and has the least risk to deflect the bed when actuating). Especially the [BFP-HS variant](https://github.com/majarspeed/Unklicky/tree/main/Unklicky_Probes/BFP-HS) is recommended.  
These limitations of the bed make the BOM VSW unsuitable for Voron Tap as well.  

You will also need the dock, mounting arm and spacer.
The Unklicky repository is forked [here](https://github.com/jlas1/Klicky-Probe/tree/main/Probes), which can be a bit confusing.  This repository has the [config files](https://github.com/jlas1/Klicky-Probe/blob/main/Klipper_macros).  
To understand the wiring, here is a drawing of the Unklicky probe. It is similar enough to Unklicky BFP-HS.

<a href="https://github.com/majarspeed/Unklicky/raw/main/pictures/BFPContact.png"><img src="https://github.com/majarspeed/Unklicky/raw/main/pictures/BFPContact.png"  width="518" height="285" ></a>

## bed
[Silicone tube bed leveling mod](https://www.schweinert.com/silicone-bed-level-mod-prusa-mk3/)

## enclosure
[Panel mounting with screws](https://github.com/hymness1/Switchwire_Things/tree/main/VSW_screwed_panel_mounting)
