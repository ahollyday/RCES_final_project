# Project Proposal RCES
Andrew Hollyday

### Project Question:
What is the wavelength and spatial distribution of dynamic topography (DT) in eastern Argentina?  

   - How do DT model results compare with spatially-diverse shorelines from the Pliocene and late Pleistocene (MIS 5e)?
   - How does mantle convection (flow velocities) vary throughout a simulation?  Is the subducting Nazca Plate resolvable in the simulation and how does it interact with flow velocities?

### Analysis

- I will use model output from the open-source 3D mantle convection code [ASPECT](https://aspect.geodynamics.org) and the python package [yt Project](https://yt-project.org) to visualize the mantle flow field and temperature on mapview and 2D cross-sectional slices through time.  
- I will also use the [yt Project](https://yt-project.org) to implement a global mapview on model output.  
- Lastly, I will correct DT model output for plate motion over the timespan of the simulation and quantify misfit from modern known point elevations.  
