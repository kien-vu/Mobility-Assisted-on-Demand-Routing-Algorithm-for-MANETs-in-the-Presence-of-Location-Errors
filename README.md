
This is a code package is related to the following  article:

Trung Kien Vu and Sungoh Kwon, “Mobility-Assisted on-Demand Routing Algorithm for MANETs in the Presence of Location Errors,” 
The Scientific World Journal, vol. 2014, Article ID 790103, 11 pages, 2014. doi:10.1155/2014/790103


#Abstract 

We propose a mobility-assisted on-demand routing algorithm for mobile ad hoc networks in the presence of location errors. 
Location awareness enables mobile nodes to predict their mobility and enhances routing performance by estimating link duration and selecting reliable routes. However, measured locations intrinsically include errors in measurement. 
Such errors degrade mobility prediction and have been ignored in previous work. 
To mitigate the impact of location errors on routing, we propose an on-demand routing algorithm taking into account location errors. To that end, we adopt the Kalman filter to estimate accurate locations and consider route confidence in discovering routes. Via simulations, we compare our algorithm and previous algorithms in various environments. 
Our proposed mobility prediction is robust to the location errors.

#Content of Code Package

The paper contains a modified-AODV routing algorithm, which implements the mobility prediction based AODV routing algorithm. 
Requires:
Operating System: Ubuntu 10.04 http://old-releases.ubuntu.com/releases/10.04.3/
Network simulator 2 http://www.isi.edu/nsnam/ns/
AODV routing algorithm: Which may require you to do some modifications based on the paper to get the simulation results.


License and Referencing

This code package is licensed under the GPLv3 license. If you in any way use this code for research that results in publications, please cite our original article listed above.
