# KiCad_Internal_Connections
a Library for KiCad 9 with Connector-Symbols for internal connections

I found it during my apprenticeship annoying to create circuit diagrams in KiCad with internal connections between the pcb and some periphery
because in professional schematics both sides of an internal connection have the same reference (with an index). In KiCad that causes many
problems with the annotation and with the functions like automatical annotation. So I created a Library that has both sides of an 
internal connection as different units of the same symbol. Unit A are the pins, this is usualy the part on the pcb. Unit B are then the part with 
the cables. It's not necessary to exclude Unit B from the pcb as both Units are the same Symbol and have only one footprint together. The 
reference is "X" like connections in the german standards are named with "X". The library includes connectors with 1 till 60 pins.

To use the library place both units of the selected Symbol next to each other and choose at the symbol-footprint-connection the footprint of the
planned real connector.
