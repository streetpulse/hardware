hardware
========

all hardware for streetpulse, that's sensors, wireless communication and receiver.


Sensors
========

You will find the Eagle file to make the sensors from scratch aka 
- garbageSensor.brd 
- garbageSensor.sch

We used a Hammond 1551LFLBK for the enclosure but other boxes might do.


Base
====
The "base" that receives data is a Raspberry Pi with an antenna and a wireless transceiver from Sparkfun
(https://www.sparkfun.com/products/705), see pictures in the base folder. Note that we first tried to use
an arduino wireless Shield for this (that's the picture) but the performance were too poor.
