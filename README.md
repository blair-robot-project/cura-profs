# Cura Profiles for 449 Printers

I (Chris) wrote some Cura slicer profiles for the Rep 2 and filaments that we have, since Makerbot's software is kind of terrible. 

## Instructions

Create a new Custom FDM printer with the settings listed in rep\_2\_cura.ini. 
Then, import the Custom Draft quality profile and the Makerbot PLA profile in Cura settings. 
Select these in the sidebar on the right of the window. 
You may want to go into Settings > Configure Settings Visibility and enable some of the things that are changed in the draft profile, in case you need to change stuff. 

## Notes

Use Cura 3.1, at least. Currently, the default\_material\_print\_temperature variable doesn't update, so make sure that the M104 S210 T0 gets changed to M104 S220 T0, since Makerbot PLA only prints at 220+.

## Licence
GPL 3.0

## Bugs and stuff
File an issue; I'll see what I can do.
