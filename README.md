# TascamDR40usbc

This is an adapter PCB that replaces the DR-40's USB mini port with a host charging capable USB C port.

![Installed mod](images/finished.png)

![Assembled mod](images/assembled.jpg)

# Why/About

I have done USB C mods to many of the devices I own, and I wanted to make one for my DR-40. This may also work on a DR-40X, but I do not own one to confirm this. This may work on any SMD USB mini port, I have used this pcb on several devices that are not the DR-40.

This mod uses 0402 SMD resistors and a small pitched USB C port, so it will require some soldering experience.

# What you'll need

The PCB, of which gerbers are available for in the [releases](https://github.com/circuitsable/TascamDR40usbc/releases/tag/gerbers). It has to be 0.8mm thick to stay within the USB mini's original footprint/volume. The PCB can be ordered from any board house, but some may not like the castellated holes or charge extra for them. **This PCB will most likely violate the anular ring sizes for your board house.** [Oshpark](https://oshpark.com/#services) will do castellated holes, has 0.8mm availability, is quite cheap, and tolerated the anular ring size violations, but the finished boards may require post processing with a small knife.

2 0402 4.7k SMD resistors. They can be sourced from anywhere, here are some examples: [Aliexpress](https://www.aliexpress.us/item/3256801250708458.html), [Ebay](https://www.ebay.com/itm/233161891164), [Mouser](https://www.mouser.com/ProductDetail/Vishay-Dale/CRCW04024K70FKED?qs=Jz%252BxJjKhzTxI08uguE%252B9mA%3D%3D), [Digikey](https://www.digikey.com/en/products/detail/yageo/RC0402FR-074K7L/2827563)

1 GCT 16 Pin 4105 Horizontal SMD USB C Port. They can be sourced from anywhere, here are some examples: [Aliexpress](https://www.aliexpress.us/item/3256806167232408.html), [Ebay](https://www.ebay.com/itm/165653029078), [Mouser](https://www.mouser.com/ProductDetail/GCT/USB4105-GF-A?qs=KUoIvG%2F9IlY%2FMLlBMpStpA%3D%3D), [Digikey](https://www.digikey.com/en/products/detail/gct/USB4105-GF-A/11198441)

Basic soldering equipment.

Hobby knife.

Needle nose pliers.

File/Side cutters (Optional).

# Installation

Disassemble and remove the USB mini port from your DR-40. This can be destructively to the original port (as long as pads are kept intact), or with a hot air station. Use solder wick to make the removed port's pads flat. If your DR-40 has a metalic mesh tape loop ontop of the USB port, keep it safe for later.

Touch up the castellated holes of your PCB with a hobby knife, as they will most certainly arrive with excess material from the pads being drilled. You may also need to file/cut off excess PCB material from its original paneling. 

Seat the USB C port as forward as it will go on the pcb, and solder **only the front two legs** of it to keep it positioned. Next, solder the USB C port's 12 pins to the PCB. Afterwards, solder the two resistors onto their footprints while being careful to not bridge any pins. 

Allign the adapter PCB into the silkscreen of the removed USB Mini port, trying to allign it down the middle as best as possible, as well as leaving as little pad depth as possible. Solder the USB C port's shield to the 4 shield pads onto the DR-40 PCB. Finally, solder the adapter's castellated holes to the old USB data/power lines. 

Double check all of your work for shorts, especially the castellated holes. Touching up shorts tends to move the resistors, so remain patient. Clean up flux residue. If your DR-40 came with a metalic mesh tape piece ontop of it's original USB mini port, place it ontop of the USB C port.

Use pliers to bend a bit of the shielding between the digital and analog board to make room for the USB C port, as shown in the image below.

![Bent shield](images/shield.jpg)
 
Remove plastic as shown in the image below from the casing to make room for the USB C port. This can be done neatly with a hobby knife and some files. Reassemble enough to test.

![Removed Plastic](images/casemod.jpg)

# PCB Images

![PCB Front](images/front.jpg)

![PCB Back](images/back.jpg)
