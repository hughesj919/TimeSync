#TimeSync
####Jordan Hughes
####UC Santa Barbara
####hughesj919 at gmail.com

Every computer has an internal clock, and, because of the physical nature of clocks, there is a tendency for clocks to drift or deviate over time from the actual time. This small project was for a distributed systems course in which we were to synchronize our local clock using time information obtained from a set of 5 servers around the world. The code originally contained the IP address and ports for those time servers, but this is taken out of the current code (those servers were not maintained past the length of the course).  For a little more info on clock synchronization see the following resources:

* (Clock Synchronization)[http://soft.vub.ac.be/~tvcutsem/distsys/clocks.pdf] - A great overview of clocks and how they function within distributed systems 
* (Cristian's Algorithm)[https://en.wikipedia.org/wiki/Cristian%27s_algorithm] - A common algorithm used for syncing a clock based on a single time server
* (Marzullo's Algorithm)[https://en.wikipedia.org/wiki/Marzullo%27s_algorithm] - A method for using multiple time servers to resynchronize a local clock

Also please see the TimeSync.pdf file for the entire project write-up.
