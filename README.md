# CNP-and-Agents-in-Electric-grid



# Super-quick Overview #

This projects simulates an environment where the electric vehicles approaches the battery station when they 
feel like filling the battery. In the peak hours, When there is more demand for power, the battery station 
requests the idle cars to act as a power store.Technically, there are three types of agents batteryStation,
car and idleCar. The batterystation uses CNP and call for proposal when there are any free slots. The cars 
can either accept or reject the proposal based on the distance and battery level. The battery station accept
or rejct the proposal by considering the availability of the free slots, waiting time and urgency level of 
the car. During peak hours, the battery station request the idle cars to supply power back to grid.
	

-------------------------*------------------------*-----------------------*---------------------------------


This project uses GAMA which is a spatially explicit agent-based simulations.

# To Run #

* Make sure that GAMA version 1.8-rc2 or greater is being used.
* Unzip the Assignment2.zip folder 
* Right click anywhere on the Models tab(left) in the interface -> Import -> GAMA Project
* Select the unzipped folder
* Execute the experiment(electricVehicles) available in `Assignment2.gaml`.


-------------------------*------------------------*-----------------------*---------------------------------
