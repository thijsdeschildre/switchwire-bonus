You can enable filament changes on the same layer, to get these very fancy prints:

<a href="https://github.com/thijsdeschildre/switchwire-bonus/blob/main/images/VS426_900.jpg"> <img src="https://github.com/thijsdeschildre/switchwire-bonus/blob/main/images/VS426_900.jpg"  width="900" height="300" ></a>

To achieve this in Prusaslicer
+ Go to "Printer settings", set the number of extruders to 2 and enable "Single Extruder Multi Material"  
+ Go to "Custom G-code" and comment the first line of "Tool change G-code" (set it to ";T{next_extruder}") and add "M600" to "Color Change G-code"
+ Go to "Print Settings", click "Advanced", enable "Clip multi-part objects"
+ Load a MMU model: you can load an STL or STEP file with multiple parts, or multiple separate STL/STEP files. Prusaslicer will ask you to load multiple as one MMU model. Click "yes"
