When checking the [sourcing guide](https://vorondesign.com/sourcing_guide), make sure you also check the toolhead (Stealthburner) parts. These are not (or not entirely) included in the VSW BOM.  

### wiring
There are specific requirements for the wiring because of the cable chains. You want wiring with PTFE mantles, with high strand count, for the best quality and durability.
On Aliexpress you can find PTFE wiring for a reasonable price. People often take 22AWG instead of 24AWG.  
Silicone wiring was recommended before, but isn't as durable. Any cabling that doesn't go through a cable chain has no specific requirements.  
You will need 2 extra end pieces for the cable chains. The BOM lists 2 pieces of 1 meter, but you have to split this up into 3 chains. You can buy spare endings, or [3D print them](https://www.thingiverse.com/thing:4894472).
  
Recommended wire lengths: a typical build has 140-160cm of wiring between the driver board and toolhead. I recommend to get a bit of spare wire. Leave the wires a bit longer at first. Later on, you can trim the cables to exact length. You cut off the JST connectors, so you'll need plenty of extra crimps.
Toolhead 22-24AWG: 4 wires for the fans, 4 for the extruder motor, 2 for thermistor, 3 for Z-probe, 2 for endstop.  
Toolhead 20AWG: 2 wires for heater.  
Heatbed: 16AWG, 2 wires for bed heater.  
Heatbed: 22-24AWG: 2 wires for endstop, 2 wires for thermistor.  
Stepper motors have their own wires, which you cut to length. Otherwise, the X motor is about 70-80cm, Y is 25-35cm, Z is 30cm. Make sure you have these JST connectors as well. When ordering JST connectors, you might as well order 5-pin and 7-pin connectors and sockets for the accelerometer.
The LCD cable is about 70cm long.

Heatbed ring terminals not in BOM ( the assembly manual says to use ring terminals. its more reliable too, AFAIK). Screw the ring terminals on the bottom of the heatbed with an M3 button head screw. These are M3 size, suitable for 16AWG.

The toolhead PCB's are optional. 

### crimping
For crimping quick disconnect terminals on the power connectors: TE 2-520184-2 from the BOM isn't compatible with generic crimp tools, it requires a unique crimp tool from TE, which costs >250 euro. The correct crimp to recommend is 640903-1 for 18-22AWG and 640905-1 for 14-16AWG.  
See https://www.eevblog.com/forum/chat/more-expensive-crimps-harder-on-the-tools/msg4175500/#msg4175500 .

### other
The BOM says "Keystone CAT6 Insert" but its not in the sourcing guide. An USB keystone is optional.
The SKR mini needs an LCD adapter, not this in BOM or sourcing guide. The assembly manual mentions it, and you need it for the recommended driver board (skr mini V2/V3)). [This](https://lab4450.com/product/skr-mini-e3-screen-adaptor/) is an example. There's also some confusion with earlier SKR mini V2 boards which required you to flip the housing of the connectors (Google it).  
You'll need thread locking fluid, blue Loctite 242.
