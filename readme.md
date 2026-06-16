Some snippets concerning mixed language programming using Microsoft programming languages for MS-DOS of the 1980s.

Mixed Language Programming with Microsoft Programming Languages
===============================================================
This Rosetta stone survival set serves as an example for using identical 
assembler routines in FUNC.ASM with various Microsoft programming languages
for MS-DOS:
- Microsoft Fortran 3.31
- Microsoft Pascal 3.31
- Microsoft Quick Basic 4.5
- Microsoft Quick C 2.5
[- Microsoft Cobol 5.0 (modifications to the assembler code were required)]

The main directory contains the tools MASM.EXE and LINK.EXE, as well as the 
assembler source code in FUNC.ASM which is used by all languages except Cobol.
A minimal set of compiler files and libraries for the individual languages are 
placed inside the directories FTN, PAS, BAS and C (in general, you should
install the complete development system for your language of choice).

Each of these directories contains a batch file GO.BAT which compiles,
assembles and links the example program ASM.EXE.
All these compiled programs should produce the same output.
If you want to use the full feature set of each compiler you should get the 
original distributions and install them on your system.
For Cobol only the source files and a batch file have been provided.

For more details see the file README.TXT.
