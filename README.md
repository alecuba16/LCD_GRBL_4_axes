# 
This is an offline controller for a CNC machine with GRBL V1.1. (4 axes version)

It executes the basic functions, such as:\
-Displaying the status of the machine \
-Move the axes \
-Auto Home ($H) \
-Unlock grbl ($X) \
-Make position 0 (G92 on all axes) \
-Read a MicroSD and send the commands to the machine \
-Modify in real time the speed of movement of the machine \
-Modify in real time the spindle RPM \
-Among other options that will be added

Components: \
-Arduino Mega \
-Rotary encoder \
-SPI microSD card reader \
-Button for E-STOP \
-LCD screen with i2c module

The box to be printed can be downloaded from the following link: \
https://www.thingiverse.com/thing:4354456

The file to compile from Arduino IDE, is in the folder LCD_GRBL/src/Codigo.ino

If you want to work from VSCode and PlatformIO, import the folder containing \
the platformio.ini file. This folder already has the necessary libraries for the \
operation of the project, so it will not be necessary to download them.

If you want to collaborate with the project, you can do it through PayPal
https://www.paypal.com/paypalme/cguerrero1205
