# Grids Through-Hole

Grids through-hole is a through-hole adaptation of the Mutable Instruments Grids Topographic drum sequencer. It’s a 100% non-commercial effort developed purely for own educational purposes where I’m trying to learn to understand schematics, Kicad and PCB making.

Please note that this is not yet tested or verified (2020-05), I’d like to hear your feedback if you built this unit so I can improve these files.

/ Design<br>
The original SMD PCB is all-in-one but since there's no space for THT components and keep the original control layout I needed to add secondary PCB for the "Brains". Basically this can be built without the Control board if you use wires from board (from PINS outputs) to output jacks, switch and potentiometers. Note that there's couple resistors and leds on the Control board. I also added those two bonus outs (clock and random gates) to the Control board upper right corner, these are not necessary to connect like in the original. Also wire connects to MIDI is moved to Brains board, this requires wires to MIDI connector.

/ Panel<br>
Original should work fine, if you want to use the bonus outs drill two holes to the panel upper right corner for jacks.



# Notes
Original files, code & BOM can be found here: https://github.com/pichenettes/eurorack/tree/master/grids
<br>Note that BOM needs convert from SMD to THT components.

# License
Hardware: cc-by-sa-3.0
