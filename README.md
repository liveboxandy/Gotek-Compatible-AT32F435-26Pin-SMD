Initial schematic and gerbers for a Gotek(?) compatible with an Artery AT32F435RGT7 chip and a 26 Pin FFC connector using SMD components.
Used SFRKC30.AT4.35 PCB for most of the schematic and layout but used SFRC2D.B PCB for the 26 Pin FFC connections.
Used photographs and a multimeter along with removing U1 and U3 on the SFRKC30.AT4.35 to get to the traces underneath.
Where possible I followed the original PCB routing of the SFRKC30.AT4.35 but Kicad has some different rules for trace widths (between pins 5&6 of U8, which isn't fitted for FlashFloppy).
Using SMD components required a few more routing changes but electrically it is still good. What a pain in the ass to find SMD parts that don't cost a fortune and have Kicad mod and sym files.
Restructured folders
Added all non pop components so that ibom displays everthing
Added ibon (bom.ibom.html)
U8 not fitted for use with FlashFloppy.
LEDS 3 & 5 are not normally fitted

Works as a replacement for the floppy in a TDS3052 Oscilloscope. Just needs a very slim case (13mm)
