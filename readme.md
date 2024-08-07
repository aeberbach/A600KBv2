A few years ago I made my first Amiga 1200 mechanical keyboard and soon after people asked me for an A600 keyboard, a kind person loaned me an A600 and I made one.

Here is version 2. At the time of the last keyboard, low-profile keyswitches existed but were hard to find and often could not use MX-stem caps, now it is easier. I'm typing this with a Nuphy Air75 v2 with "Gateron x Nuphy Moss" KS-33 switches and the feel is amazing. There is a lighter variant "Wisteria" and a regular brown tactile option. Blue (clicky) and several variants of linear including red are available too. These switches use a different footprint to standard MX so the PCB had to be redone.

The low profile switches do not come in a 5-pin PCB mount version so a plate is essential. While laser-cut would be amazing I don't have a laser cutter, also that would not be 3-dimensional and would not leave space for the stab wires. To keep it printable on common 3D printers the plate is in two pieces. I have used eSun "milky white" PLA which is opaque and a very good match for an Amiga case. The stabilizers mount to the plates, the holes in the PCB underneath are only for clearance. These plates keep the keyswitches perfectly straight during assembly, improve keyboard stiffness, dampen sound and make for a better appearance.

This keyboard mounts to the case by two 3d printed rails that attach to the top and bottom of the keyboard. They are keyed so as to locate correctly and also to help keep the edges of the plates from lifting. Because the plates and rails are printed with PLA the best way to attach is with a small amount of cyanoacrylate glue. If you get too much running into the wrong places your keyboard is toast, so don't use ultra-thin that will wik everywhere and don't use too much!

One thing that hasn't been done is to source a Caps Lock key with a window for the LED. The LED mount is still there and you can put a LED under the switch but I don't know where you can get a windowed keycap for it. The LED section of this keyboard includes a circuit where it will light an alternate LED for power when Caps Lock is active. My keybaord has a red LED for power but that changes to blue when Caps Lock is activated.

If you don't want to use the LED function of this keyboard you can just snip away the top right of the PCB and use the original Amiga 1200 LED PCB. In that case don't bother with LEDs, capacitor, resistors or the inverter chip.

Requirements:

    one PCB (see the 'fab' folder for gerber files, ready to build)
    78 Gateron KS-33 keyswitches
    2 Gateron 2U plate-mount low-profile stabilizers
    1 more Gateron low-profile stabilizer to disassemble - bend your own wire from 1.0mm music wire, available from hobby stores.
    0805 LEDs: red, green, yellow and blue (or whatever colors you like for the various functions)
    0805 10k resistor (R6) 
    0805 current-limiting resistor for each LED. Choose a value not less than 300 ohms. If your LEDs are too bright you can use higher values. I found that red/blue need around 1k, yellow/green 390 ohms. (R2, R3, R4, R5) Your LEDs may vary.
    0.1uF 0805 decoupling capacitor
    SN74LVC2G04DBVR dual inverter (available Mouser electronics)
    4-pin dupont housing, pins and ribbon cable to connect LED section to Amiga
    one FFC connector, 32-way RA 1.25mm pitch. Molex 52044-3245 (available Mouser Electronics)
    one FFC ribbon cable, 32-way, 1.25mm pitch. Molex 15168-0400 (available Mouser Electronics)
    Printed plate to house stabilizers and switches on top of PCB (STLs in 3dprint folder)
    Printed mounts to secure the keyboard in your case (STLs in 3dprint folder)
    78 Amiga keycaps: user Steveed on Amibay recently sorted this out with Signature Plastics and they are perfect.

The cost of all this varies with the cost of PCB manufacture, keyswitches and stabilizers and of course the keycaps. As a very rough guide expect to pay no less than about:

    PCB $20
    keyswitches $30
    stabilizers $20
    LEDs and other components $2
    FFC connector and cable $8
    3D printed parts $10

And assembly will take at least three hours. That's just under $100 in parts alone and does not even count a quality set of keycaps at around $130. (But if you weren't slightly obsessed you probably wouldn't have an Amiga in 2024.)

The license for this keyboard is non-commercial. However if a person has ordered the minimum of 5 PCBs from one of the usual places and wants to offer the extras for sale that is reasonable.

License: CC-BY-NC-SA 4.0
