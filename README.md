Metroid for MMC3
===========
This is the disassembled source code of METROID for the Nintendo Entertainment System (NES). You can reassemble the source code using the included assembler (Ophis v2.1, built for Windows/bundled for *nix), or a build of the [latest version of Ophis](https://github.com/michaelcmartin/Ophis).

Features
-----------
The original version of METROID used the [MMC1 memory controller](http://wiki.nesdev.com/w/index.php/MMC1). This version has been changed to use the improved [MMC3 memory controller](http://wiki.nesdev.com/w/index.php/MMC3). The source code is also better organized, better labeled, better commented, and omits much of the code and data which was unused in the original game. Because of these omissions, reorganizations, and the change in memory ASIC, the assembled binary of MetroidMMC3 will not be identical to a rip of the original METROID ROM. However, it will run identically to the original METROID (except for insignificant differences in timing - MetroidMMC3 runs a few cycles faster than the original in limited circumstances; frame timing remains identical).

MetroidMMC3 would be an ideal foundation for anyone who is interested in creating a modification or total conversion of METROID for the NES.

Building MetroidMMC3
-----------
This repository includes a rudimentary make system for Windows and *nix. You can assemble the latest version of MetroidMMC3 by running the "make_txrom" script appropriate for your platform. You can also assemble the original disassembly of METROID (for the MMC1) by running the
"make_original" script.

Please note that compiling Metroid for MMC3 on *Nix requires WINE.

History of the METROID Disassembly
===========
MetroidMMC3 is based on the original disassembly of METROID (created by Kent Hansen), which has been further organized and commented by Nick Mikstas. A more detailed history of the METROID source code is available online at the [Metroid Database](http://www.metroid-database.com/m1/sourcecode.php).

*nix support was added by [Adam D.](https://github.com/adam820).