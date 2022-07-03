Two folders are provided whether the Magnetic Gear is used as Torque multiplier o reducer:
	- Torque_set_on_sun	->	Torque multiplier; Torque on Sun, Speed on Ring
	- Torque_set_on_ring	-> 	Torque reducer; Torque on Ring, Speed on Sun


	On the subfolder there are 2 possibilities:
		- Flux_Time		->	Magnetic Flux acquisitions
		- Torque_Speed 		->	Torque and speed acquisitions
	
	
		On the subfolders:
			- Load		-> Resistent Torque applied
					- Consists into a series of constant T applied, refer to DOE table

			- Noload	-> No resistent torque applied, only speed
					- Consists into a seriers of rise and fall tests.
					- Radial and Tangetial flux are provided for the Flux_Time case.

NOTE:
	-For Flux_Time case:
		-Name of each test refers to the applied speed:
			- Into Torque_set_on_ring, Ring speed is takent into account
			- Into Torque_set_on_sun, Sun speed is taken into account

	-For Torque_Speed case:
		-Name of each test refers to the applied speed:
			- Always referred to the Ring speed