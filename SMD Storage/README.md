# SMD Storage
The designs herein are based on the designs made by Robin Reiter, published on [hackaday](https://hackaday.io/project/168275-smd-component-magazines) and [thingiverse](https://www.thingiverse.com/thing:3952021).

## Differences to the Original
The designs published here are compatible with the originals.

I call the "magazines" for cassettes as that word closer resembles their design and function with a wound tape.

* I have added a lip on the bottom of the cassette and sealed the gap by the tape exit nozzle to prevent cut tape from falling out of the casettes so easily. Makes transporting and storing them easier.
* I have changed the design of the rail to allow larger volumes of ballast and granular ballast like sand.
* No spring clipped version is provided as I consider the compliant hinge design to be superior from a simplicity and manufacturing PoV.

# Printing
All the designs are designed to print without support. Please see the example slicer files for PrusaSlicer. The GCODE files provide are intended for printing with a MK3, although they might work with your printer there is no guarantee that the prints will succeed or come out nice. Please consider rlicing the STL files to fit your printer.

The casette is designed to be printed laying flat on the closed side. Most, if not all, 3D printers can bridge the gap in order to print the big bottom lip without any support. If the lip is not turning out good, check your bridging settings in your slicer or try reducing the layer height. I found that using 0.3mm layer height caused large bumps on the front side of the bottom lip, printing the first few bridging layers with 0.2mm or lower layer height fixed this.

The rail is designed to be printed standing on one end, this means that the compartment walls will be bridged. You're also printing a tall object so adding a brim is recommended to avoid warping and delamination from the print bed. Note that the XY lateral force becomes larger on the bottom layer as the print builds up height. If the print fails due to delamination/warping, try a larger brim, slower print speed, reducing drafts in the room (windows, fans), adjusting the bed temperature or using some type of print adhesive on the bed.

Other than the bottom lip on the cassettes, all parts lend them selves well to be printed with high layer heights. For material I used PLA without any issues.

## Faster prints
You will likely be printing a fair few cassettes so print speed matters. I found great success by printing 4 cassettes at a time using sequential printing and variable layer height (0.3mm everywhere except the bottom lip on the cassettes where I aim for 0.2mm). Two perimiters is enough if you have infill, I would probably use 3 if printing without infill, which is possible but a bit rough when briding the first solid top layer, but it worked for me.

# Assembly Instructions
The [original video](https://youtu.be/XrnoqusTrHg) and [build instructions](https://cdn.hackaday.io/files/1682757199477600/Build%20Instructions.pdf) are still useful to understand the general function of the system. 

The cassettes need no further assembly after printing, just clean them up, remove any stringing etc. Ready to use.

Although not strictly necessary, the rail works best if you fill the compartments in the back with some form of ballast (screws, nuts, washers, truss connector plates, sand, lead beads, whatever heavy thing you can find that fits in there) and then use hotglue or cyanoacrylate glue to fix the lid in place. I recommend adding hot glue in with the ballast as well to prevent it from moving around, making a racket and possibly damaging the plastic on the inside. Mind the hotglue temperature as it can be close to Tg of the material you printed with.

Although Robin mentioned difficulties with the labels staying attached to the printed surface, I have not experienced that problem when using a Dymo Letratag with original Dymo labels and cassettes printed with PLA on a Prusa i3 MK3s.

# License
[**CC BY-NC 4.0**](https://creativecommons.org/licenses/by-nc/4.0/)

Modified designs published with permission.



