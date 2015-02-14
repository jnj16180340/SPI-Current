# SPI-Current
Schematic and boards for power supply  

**TODO:**  
* Wall voltage fuse, stepdown, rectify, filter
* Make a branch with 2 independent half bridges in it
* Isolate the 12V stuff from the 5v stuff (add optoisolators)
* Figure out filtering caps for hall sensors
* Add fuse to output
* Lay out boards  


**NOTES:** 
* Use 10 gauge wire
* Replace shunt resistors x2 with thick wire jumper, unless you omit the hall sensors
* Replace a hall sensor with wire jumper unless you want two redundant ones
* Values for L#, may depend on the load
* Gain of output buffer: If ACS758 is 60mV/A, then max (50A) is 3. Want gain = 5/3
* 12V gets an XT60 connector, rated to 60A
* So does output to peltiers
* DIS jumper disables the drivers...
* If you power up the HIP4081 backwards it DIES.




