# GeeetechChimeraFirmware
Firmware and Start and End GCODE in my Prusa Slicer I use for my Chimera 2 in 2 out Geeetech printer

Firmware is for use with the E3D Chimera 2 in 2 out hot end. There is one for the "A10M with a 3D touch" and one for the "A20M without a 3D touch".
In both cases the X and Y have been set and you can just search for "21" and you will see the offset I set for the 2nd tip to align it.

In the firmware X is 21mm and Y is 1mm - You can make X and Y 0 if you like and just set everything in your slicer. 
Settings for X: (#define HOTEND_OFFSET_X {0.0, 21.00} // (in mm) for each extruder, offset of the hotend on the X axis)
Settings for Y: (#define HOTEND_OFFSET_Y {0.0, 1.00}  // (in mm) for each extruder, offset of the hotend on the Y axis)
I chose to set it in the firmware and tweak it in the slicer as needed. I set Extruder 2 to X=-0.60mm and Y=-0.80mm under printer settings in Prusa Slicer.
Update the firmware using Arduino IDE.

UPDATE FIRMWARE AT YOUR OWN RISK

If you change your hot end to the Chimera then make sure you PID so that your temperature will maintain correctly.
This can be done on the printer in the Control->temperature setting on the A10M and A20M. Scroll down and set the PID tuning temperature and it will then perform 5 temp checks and update your PID values.
Once complete (takes about 10mins) then ensure you choose control->store settings to save the values.


