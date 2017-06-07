# N body simulation

## What the code shows
* This Jupyter notebook shows a non-object oriented approach to the n-body simulation, in which n objects interact gravitationally with one another. 
	* Positions and velocities of particles are saved as numpy arrays.
	* Accelerations are calculated for a time step dt in an O(n^2) naive algorithm.
* One could modify the code to include initial positions and velocities in order to simulate something like the solar system.