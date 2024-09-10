
# Silakka54 - Build Guide

### Bill of materials
- **54x** MX compatible key switches
- **54x** Kailh Hotswap Sockets
- **54x** 1N4148 Diodes
- **52x** 1u keycaps
- **2x** 1.5u keycap
- **2x** RP2040 Zero
- **2x** PJ320D audio sockets
- **1x** TRRS audio cable
- **20x** M2 Heat set inserts, length 2mm(OD3.2mm)
- **20x** M2 bolts, length 4mm
- **2x** PCB
- **2x** Bottom plate
- **2x** Top plate

STL files do not require support, PLA plastic works well and printing of parts has been tested with a 0.4mm nozzle. Insert the heat set inserts into the bottom plates using a soldering iron.

The PCB is designed so that it can be used on both sides. Use the images as a reference.
![Use a non-conductive tool to press buttons](https://raw.githubusercontent.com/Squalius-cephalus/silakka54/main/buildguide/image1.png)
The right side RP2040 needs to be flipped. Don't solder it too close to the PCB, leave a two-millimeter gap, the legs of the pin header should be long enough. There is no RESET pin on the Zero, so you need to have access to RESET and BOOT buttons if you want to change/upload the firmware.

**It is recommended that the firmware is already installed on the RP2040 Zero, the uf2 file can be found in the firmware folder. Double pressing the RESET button should put the Pico into bootloader mode if the firmware is installed.**

Solder the hotswap sockets, TRRS sockets, and RP2040's. Connect the two halves with the TRRS cable. Never connect or disconnect TRRS cable when keyboard is powered. This can lead to a short circuit.
![Check the pins!](https://raw.githubusercontent.com/Squalius-cephalus/silakka54/main/buildguide/image2.png)
Next, attach the PCB to the plate with bolts. Then you can attach the switches to the top plate. Once all the switches are in place, make sure that the switch pins are not twisted or damaged. Press the top plate with the switches to the PCB.
![-](https://raw.githubusercontent.com/Squalius-cephalus/silakka54/main/buildguide/image3.png)

If the PCB does not fit well with the base, cut small pieces off next to the threads. This problem will be fixed in a later version of the model.

I recommend putting small rubber feet on the bottom plate. If you installed the silakka54_vial firmware, you can use the Vial software to test the functionality of the switches in the matrix tester.
