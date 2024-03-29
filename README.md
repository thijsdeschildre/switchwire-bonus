This is a user-driven repository for the Voron Switchwire, it collects useful tips and tricks to build and configure a Switchwire.

## Intro
There are three paths to build a Switchwire:
* Self-source all parts: more expensive and very time intensive, but allows full control of the quality and configuration
* Buy a kit. LDO kits have good value. 
* Convert an Ender. I don't cover this topic, go to the Voron Discord, open the **#voron_switchwire_questions** channel, on the top right menu click the "threads" icon. There you can click your way to **#ender_conversion_chat** . Conversions are available Ender 3,  V2, Artillery and CR10.

**Make sure you read through all of the** [**documentation**](https://docs.vorondesign.com/). This covers sourcing information, building information (mechanical, electrical, software, initial setup and motor troubleshooting, your first print),  tuning and maintenance.
[LDO](https://docs.ldomotors.com/en/voron/voronsw) also has their documentation. 

## Part sourcing
Voron information to source [here](https://docs.vorondesign.com/sourcing.html).  
There is the [BOM](https://vorondesign.com/voron_switchwire), but you mostly want to rely on the [Sourcing Guide](https://vorondesign.com/sourcing_guide).  
My remarks [here](https://github.com/thijsdeschildre/switchwire-bonus/blob/main/BOM.md).  

## Assembly
Voron information to assemble [here](https://docs.vorondesign.com/build/).  
Hardware assembly [here](https://github.com/VoronDesign/Voron-Switchwire/raw/master/Manuals/Assembly_Manual_SW.pdf). Toolhead assembly for [Stealthburner](https://github.com/VoronDesign/Voron-Stealthburner/blob/main/Manual/Assembly_Manual_SB.pdf).  
Extra [LDO wiring guide](https://docs.ldomotors.com/voron/voronsw/wiring_guide_rev_a), [LDO cable chain guide](https://docs.ldomotors.com/guides/cable_chain_guide)
The enclosure isn't documented, check the CAD files. Maybe LDO has info.  
[Nero3D has assembly videos](https://www.youtube.com/channel/UCmV40QWkVeRs_nAvEOE_P-g).  
My remarks [here](https://github.com/thijsdeschildre/switchwire-bonus/blob/main/assembly.md).  
Make sure you check the [CAD drawings](https://github.com/VoronDesign/Voron-Switchwire/tree/master/CAD), assembly is a lot easier if you can visualize it.
Learn [here](https://www.mattmillman.com/info/crimpconnectors) about the myriad of crimps, connectors and tools.  
 
## Software configuration
Install the software stack microcontroller. Usually this is a Raspberry Pi with klipper, an API such as Moonraker, and a  front-end like Mainsail or Fluidd. You can find premade images for these stacks.  
There's a sample configuration for driver board [here](https://github.com/VoronDesign/Voron-Switchwire/tree/master/Firmware).  
The heatbed thermistor should work with the "Generic 3950" type.  
A sample Voron config for Prusaslicer /  Superslicer can be found on Discord (pinned messages of **#slicers_and_print_help**).  
These two config files need to be adapted further to your build. This is a learning process and part of the build. 

## Tuning
Voron information to tune [here](https://docs.vorondesign.com/tuning/).
Print tuning guide: [Ellis3D](https://ellis3dp.com/Print-Tuning-Guide/).  

## Upgrades / Expansions
See [this page](https://github.com/thijsdeschildre/switchwire-bonus/blob/main/STL.md)
