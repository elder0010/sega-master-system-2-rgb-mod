# Sega Master System 2 RGB PCB Mod with optional Sync Stripper
This is a RGB mod board for Sega Master System 2 with optional support for LM1881 sync stripper module.
It fits the RF modulator space, so you don't have to drill holes in your console.

![Board](https://bitbucket.org/elder0010/sega-master-system-2-rgb-mod/raw/254340afdaeb6ee62460daaf69f587a3cb3aba7e/Master%20System%20II%20Rgb.png)

Included in this repository:

  - Eagle project (schematics + board)
  - Gerber files (in directory CAMOutputs)

# Required parts list
In addition to the board, you will need:

 - 4x 220 μF 25v capacitors (C1/C4)
 - 1x 10 μF 25v capacitors (C5)
 - 5x 75 ohm resistors (R1/R5)
 - 7 pin mini din connector

# Optional parts list
If you wish to add sync separation capability to the board you will need:

 - LM1881N chip (IC1)
 - 2x 0.1 μF ceramic capacitors (C6/C7)
 - 1x 75 ohm resistor (R6)

# Wiring
Wire the composite, red, green, blue, audio, ground and VCC signals from the console on the input pads.
Instructions for locating the signals on the console can be found here: [Master System II RGB/S-Video Modification](http://www.smspower.org/masterful/rgb.html)

Wire the output signals to the mini din connector. The output pads Oe, Bu, Vs, Cs are for the LM1881N chip.