A few years ago I made my first Amiga 1200 mechanical keyboard and soon after people asked me for an A600 keyboard, a kind person loaned me an A600 and I made one.

Here is version 2. At the time of the last keyboard, low-profile keyswitches existed but were hard to find and often could not use MX-stem caps, now it is easier. I'm typing this with a Nuphy Air75 v2 with "Gateron x Nuphy Moss" KS-33 switches and the feel is amazing. There is a lighter variant "Wisteria" and a regular brown tactile option. Blue (clicky) and several variants of linear including red are available too. These switches use a different footprint to standard MX so the PCB had to be redone.

The low profile switches do not come in a 5-pin PCB mount version so a plate is essential. While laser-cut would be amazing I don't have a laser cutter, also that would not be 3-dimensional and would not leave space for the stabilizer wires. To keep it printable on common 3D printers the plate is in two pieces. I have used eSun "milky white" PLA which is opaque and a very good match for an Amiga case. The stabilizers mount to the plates, the holes in the PCB underneath are only for clearance. These plates keep the keyswitches perfectly straight during assembly, improve keyboard stiffness, dampen sound and make for a better appearance.

This keyboard mounts to the case by two 3d printed rails that attach to the top and bottom of the keyboard. They are keyed so as to locate correctly and also to help keep the edges of the plates from lifting. When attaching be careful not to break off the key pieces. Because the plates and rails are printed with PLA the best way to attach is with a small amount of cyanoacrylate glue. If you get too much running into the wrong places your keyboard is toast, so don't use ultra-thin that will wick everywhere and don't use too much! Medium glue will wick enough to secure them.

One thing that hasn't been done is to source a Caps Lock key with a window for the LED. The LED mount is still there and you can put a LED under the switch but I don't know where you can get a windowed keycap for it. The LED section of this keyboard includes a circuit where it will light an alternate LED for power when Caps Lock is active. My keyboard has a green LED for power but that changes to blue when Caps Lock is activated.

If you don't want to use the LED function of this keyboard you can just snip away the top right of the PCB and use the original Amiga 1200 LED PCB. In that case don't bother with LEDs, capacitor, resistors or the inverter chip.

The space bar stabilizer cannot be bought. Instead get a normal 2U stabilizer and remove the wire. Bend a piece of 1mm music wire so that the parallel wires are 133.5mm apart, and trim them to length using the 2U wire as a guide. If you do not get this within about 1/2mm or the parallel wires are not in-plane and actually parallel then your space bar will not work properly!

Requirements:

    one PCB (see the 'fab' folder for gerber files, ready to build)
    78 Gateron KS-33 keyswitches
    2 Gateron 2U plate-mount low-profile stabilizers
    1 more Gateron low-profile stabilizer to disassemble for the space bar
    0805 LEDs: red, green, yellow/orange and blue (or whatever colors you like for the various functions)
    0805 10k resistor (R6) 
    0805 current-limiting resistor for each LED. Choose a value not less than 300 ohms. If your LEDs are too bright you can use higher values. I use 1k ohms, your LEDs may vary.
    0.1uF 0805 decoupling capacitor
    SN74LVC2G04DBVR dual inverter (available Mouser electronics)
    4-pin dupont housing, pins and cable to connect LED section to Amiga
    one FFC connector, 32-way RA 1.25mm pitch. Molex 52044-3245 (available Mouser Electronics)
    one FFC ribbon cable, 30-way. You can trim two circuits from Molex 15168-0400 (available Mouser Electronics) or look on AliExpress.
    Printed plates to house stabilizers and switches on top of PCB (STLs in 3dprint folder)
    Printed mounts to secure the keyboard in your case (STLs in 3dprint folder)
    78 Amiga keycaps: user Steveed on Amibay recently sorted this out with Signature Plastics and I think these are the best available. A1200.net keycaps are for the Mitsumi-style switch and will not fit.

The cost of all this varies with the cost of PCB manufacture, keyswitches and stabilizers and of course the keycaps. As a very rough guide expect to pay no less than about:

    PCB $20
    keyswitches $30
    stabilizers $20
    LEDs and other components $2
    FFC connector and cable $8
    3D printed parts $10

In quantities of one - it gets cheaper when you buy in bulk of course. And assembly will take at least three hours. Obviously this is not cheap and does not even count a quality set of keycaps at around $130. (But if you weren't slightly obsessed you probably wouldn't have an Amiga in 2024.)

The license for this keyboard is non-commercial - no stores may build and sell this project. However if a person has ordered the minimum of 5 PCBs from one of the usual places and wants to offer the extras for sale at near cost, once, that is reasonable.

Thanks to Steveed (Amibay) and to everyone that has supported this project. 

License: CC-BY-NC-SA 4.0