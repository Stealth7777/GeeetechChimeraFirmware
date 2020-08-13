# GeeetechChimeraFirmware
Firmware and Start and End GCODE in my Prusa Slicer I use for my Chimera 2 in 2 out Geeetech printer

Firmware is for use with the Chimera 2 in 2 hot end. There is one for the A10M with a 3D touch and one for the A20M without a 3D touch.
In both cases the X and Y have been set and you can just search for "21" and you will see the offset I set.
Update firmware uusing Arduino IDE.

UPDATE FIRMWARE AT YOUR OWN RISK

If you change your hot end to the Chimera then make sure you PID so that your temperature will maintain correctly.
This can be done in the Control->temperature setting on the A10M and A20M. Scroll down and set the PID tuning temperature and it will then perform 5 temp checks and updaet your PID values.
Once complete (takes about 10mins) then ensure you choose control->store settings to save the values.


