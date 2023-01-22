# PLCC-ADB-Adapter
A PIC16F88/87 based replacement for Apple PLCC ADB Controller using Tashtari's port of the original ADB controllers firmware

# Assembly
Solder a QFN PIC16F88 or PIC16F87 to the adapter PCB
Thats it!

# Programming
The PIC can be programmed on the adapter by temporally soldering jumper wires to the adapter PCB and connecting these to a Pickit 2/3 or other compatible programmer

All pin numbers stated below refer to the pins on the adapter PCB and not the PIC  
VCC - Pin 22  
GND - Pin 7  
PGD - Pin 20  
PGC - Pin 21  

When initially testing this I had some issues with MPlab 8 not wanting to program the PIC, it seems for whatever reason MPlab 8 programmed a incompatible firmware onto my Pickit, this was fixed by opening MPlab X and getting it to program the correct firmware onto the Pickit after which MPlab 8 was able to successfully program the PIC. This may have been a fluke but if you have trouble getting the PIC to program it's worth a try!

# Code
The code for the PIC can be downloaded from [Here](https://github.com/lampmerchant/macseadb88)
