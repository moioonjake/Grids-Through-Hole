# Grids Through-Hole

Grids through-hole is a through-hole adaptation of the Mutable Instruments Grids Topographic drum sequencer. It’s a 100% non-commercial effort developed purely for own educational purposes where I’m trying to learn to understand schematics, Kicad and PCB making.

Please note that this is not yet tested or verified (2020-05), I’d like to hear your feedback if you built this unit so I can improve these files.

# Design
The original SMD PCB is all-in-one but since there's no space for THT components and keep the original control layout I added secondary PCB for the "Brains". Basically this can be built without the Control board if you use wires from board (from PINS(1-3).1 outputs) to output jacks, switch and potentiometers. Note that there's couple resistors and leds on the Control board so without the Control board add these to the jacks and switches.
<br><br>I also added those two bonus outs (clock and random gates) to the Control board upper right corner, these are optional like in the original. Also wire connect points to MIDI is moved to the Brains board, this requires wires to MIDI connector or add stereo 3.5mm jack and wire MIDI from Brains board to that.

# Panel
Original should work fine as the Control board layout as kept as original, if you want to use the bonus outs drill two holes to the panel upper right corner for jacks.

# Possible updates to v1.2
- Add: MIDI output to stereo 3.5mm jack to Control board. On the PINS3.x GND can be changed so that MIDI would be transported via PINS3.x pin 1/6 between boards. Add stereo 3.5mm jack to Control board and wire to the PINS3.2 1/6 and on the Brains board wire MIDI RX/TX to PINS3.1 1/6.

^ katso PIN3.x GND!!
^ katso RX vai TX

# Notes
Original files, code & BOM can be found here: https://github.com/pichenettes/eurorack/tree/master/grids
<br>Note that BOM needs convert from SMD to THT components.

# License
Hardware: cc-by-sa-3.0
