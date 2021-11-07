# ROMS with or without delay 

This folder provides ROMs with different delays before starting the initialization of the video card or the detection of the sound card. 

This feature can be enabled or disabled from the configuration file (config.inc):

%define INIT_DELAY      100             ; Initial delay in miliseconds before BIOS starts, to allow time for some ISA cards to be initialized.