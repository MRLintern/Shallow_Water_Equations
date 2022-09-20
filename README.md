#### Shallow_Water_Equations

Application of the Shallow Water Equations to Oceanography & Planetary Atmospheres.
[see here](https://en.wikipedia.org/wiki/Shallow_water_equations)

### Requirements
* `MATLAB`. Version 2020b was used but it shouldn't matter which one you use
* `OS`. `Ubuntu 20.04` was used however `Windows 10` will be fine. All thats needed is that you have `MATLAB`

### Introduction

This application demostrates a number of phenomena, including gravity waves, barotropic instability, orographic Rossby waves, geostrophic turbulence,
tsunamis and equatorially trapped waves.

The Shallow Water Equations are:

  `dh/dt + d(uh)/dx + d(vh)/dy = 0`
  
  `d(uh)/dt + d(u^2h + gh^2/2)/dx + d(uvh)/dy = h(fv - gdH/dx)`
  
  `d(vh)/dt + d(uvh)/dx + d(v^2 + gh^2/2)/dy = h(-fu - gdH/dy)`
  

  
All `d`s are partial derivatives.

  *`h` = height of water from the bottom/sea floor to the sea surface.
  *`H` = height of the orography; think of this as mass of some type on the sea floor.
  *'g' = acceleration due to gravity.
  *'u' = x-component of the velocity (flow) field.
  *'v' = y-component of the velocity (flow) field.
  *`f` = Coriolis parameter. [Coriolis parameter](https://encyclopedia2.thefreedictionary.com/Coriolis+parameter).

