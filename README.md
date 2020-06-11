msp430-gcc-4.7.3
================
Compiled binary packages of MSP430-GCC version 4.7.3

Compatible Machine:
 - x64 based linux machines

Installation Instructions:
 - Extract the tar (tar xfj mspgcc-4.7.3.tar.bz2) in a location: example (/opt/compilers/mspgcc-4.7.3/)
 - Add the location of extracted binary file path (/opt/compilers/mspgcc-4.7.3/MSP430/bin/) path to your systems' enviroment $PATH
 - edit $HOME/.bashrc and add the following line at the end of the file.
    - export PATH=$PATH:/opt/compilers/mspgcc-4.7.3/bin

Contiki-NG Instructions:
 - To use MSP430-GCC-4.7.3 when building Contiki-NG, edit contiki-ng/arch/cpu/msp430/Makefile.msp430:
 - Change the lines: \
   CC = msp430-gcc \
   LD = msp430-gcc 
 - To: \
   CC = msp430-gcc-4.7.3 \
   LD = msp430-gcc-4.7.3 

