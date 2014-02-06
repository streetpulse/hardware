hardware
========

All hardware for streetpulse are presented in this folder: that's sensors, wireless communication and receiver.
all contents on this repository are under Creative commons (Attribution-NonCommercial-ShareAlike 3.0 Unported)

![alt text](http://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png "Creative Commons Licence")



Sensors
========

The Sensors are composed of an electronic board, a battery, a solar cell and an enclosure.

You will find the PCB file (Eagle software) to make the electronic board for sensors from scratch, with the list of components used. Most manufacturers will take these files and can produce the sensor modules without additional work.

- garbageSensor.brd 
- garbageSensor.sch
- bom-street-pulse.xls
 
For the enclosure containing the modules, We used a **BUD CU-791-MB** but other boxes might do.

Regarding the solar cell, we imported a model from China, the **SZGD6060-4P**, but all models capable of 2Volts at 200mA max (max Power 0.4 Watt) would do.


Base
====
The "base" that receives data is a **Raspberry Pi** with an antenna and a wireless transceiver from [Sparkfun][https://www.sparkfun.com/products/705], see pictures in the base folder. Note that we first tried to use
an arduino wireless Shield for this (that's the picture) but  performance was too poor.

Aside from better performance, we also recommend the use of Raspberry Pi as it saves data locally before sending it to a server. 
This allowed us to cope with unreliable wifi connection and network loss of data. It also serves as additional backup.


