# VesselsSpatiotemporal

It's group project for The Process of Data Science Course. (two people project). 

**Solve a spatiotemporal problem and work with streaming techiniques**

Nima Ports dataset: Nima_Ports. 
AIS data: AISdata. 

**Tasks**
* 1. Find all the vessels that visited ports in the provided shapefile (Nima_Ports). First, create a buffer with an appropriate radius around the shape of each all polygons in the shapefile. Second, find all the AIS messages (from AIS data) that intersect with these ports.
![Image of P1](https://github.com/Pam1024/VesselsSpatiotemporal/blob/master/Screen%20Shot%202020-03-03%20at%203.34.45%20PM.png)
* 2. Show the density (i.e., density is the number of AIS messages in a port), of each port on a map by using a colour-coded map. 
![Image of P2](https://github.com/Pam1024/VesselsSpatiotemporal/blob/master/Screen%20Shot%202020-03-03%20at%203.34.57%20PM.png)
* 3. Now divide the AIS data into data frames with a one-hour interval. Repeat steps 1 and 2 for all of the sub-dataframes. 
* 4. Select a port. Create a temporal chart for the density of messages in that port.  x is the time and each snapshot of the time has the density of port at a specific hour.
![Image of P4](https://github.com/Pam1024/VesselsSpatiotemporal/blob/master/Screen%20Shot%202020-03-03%20at%203.29.03%20PM.png)
* 5. Use concept drift methods on step 4 and find out if there is any drift in the data that can be detected. 
* 6. Cluster the ports based on their message density using DBSCAN and categorize the ports based on traffic (message density) 

