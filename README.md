# AMX3 - 3-channel active mixer

A companion module to the 3-channel passive mixer - this one is active and is set up for mixing audio signals. 
The inputs are capacitively coupled and each input channel has  individually controllable gain.

This mixer was designed for use with audio signals - whilst you can use it to mix control voltages, any DC offsets will be removed.
If you're DIYing and this isn't what you want, then you will need to omit **C1**,**C2**,**C3** and **C16** and fit either wire bridges or
zero-ohm links in their place. If you decide to go down this route *hen you should seriously consider using TL084 op-amps instead 
of TL074 - 084s are far more immune to latch-up than 074s.

As supplied, the maximum gain is around 5, which should be sufficient for most cases although if you wish to change this you'll need
to use different values for **R7**,**R8** and **R9** - lower values will result in more gain. If you'd prefer unity gain (or thereabouts)
then simply set R7, R8 and R9 to the same value as the associated potentiometer

## Files

* _AMX3-BOM.xlsx_ - Bill of materials
* _AMX3-panel.dxf_ - Front panel in DXF format
* _AMX3-panel.fpd_ - Front panel in Schaeffer .FPD format
* _AMX3-panel.kicad_pcb_ - KiCAD PCB file for front panel
* _AMX3-schematic.png_ - schematic
