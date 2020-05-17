# Micro 8088 - BIOS Binary Images

This directory contains BIOS binary images.
See [8088 BIOS](https://github.com/skiselev/8088_bios/tree/master) GitHub repository for the source code.

# Update from ROM file into Micro 8088 system

uFLASH.exe -p -i biosxxx.rom -a FA00

xxx being the BIOS version to update, for example 097

# About uFLASH

This is a modification of Sergey's original app from his other project xi8088, original sources here:

http://www.malinov.com/Home/sergeys-p...

It has been made compatible at the level of timers with Sergey's Micro8088 project, and a timeout has been added before proceeding to flash the memory. This will allow, if needed, to hot swap the half that you want to program using the corresponding switch of the board.

The timeout is programmed to run at approximate speed of seconds with 4.77 Mhz CPU frequency, in configurations of 7.16 MHz or 9.54 MHz the speed will be higher.

![alt text](uflash.gif "uFLASH_in_action")

