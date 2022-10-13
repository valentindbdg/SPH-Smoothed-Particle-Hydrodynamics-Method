# SPH-Smoothed-Particle-Hydrodynamics-Method
 
Unlike the Finite Element Method (FEM), the particles used in the SPH method can be separated, and can therefore be used for many types of simulation that the Eulerian method cannot solve: 
* System enduring huge deformation
* Penetration
* Astrophysics
* Systems having more than one material (such as two fluids mixing)
* Machining
* etc. 

 
Instead of solving linear equations like the Eulerian method, the SPH method allows having mass conservation and pressures without extra computation. <br/>
The masses are contained in each particle and the pressures are given by the mathematical link between neighboring particles. <br/>
Besides, boundary conditions are required for the Eulerian method which may be unknown for some systems (like for stars in astrophysics). This is a problem that the SPH method does not have. <br/>
However, the SPH method still has some drawbacks such as computing time, consistence at the boundaries (studied in this paper), tensile instability, and spurious energy mode. <br/> 
