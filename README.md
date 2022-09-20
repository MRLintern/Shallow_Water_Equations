#### Shallow_Water_Equations

Application of the Shallow Water Equations to Oceanography & Planetary Atmospheres.
Numerical integration of the equations is performed via the [Lax-Wendroff Finite Difference Method](https://en.wikipedia.org/wiki/Lax%E2%80%93Wendroff_method).

### Requirements
* `MATLAB`. Version 2020b was used but it shouldn't matter which one you use
* `OS`. `Ubuntu 20.04` was used however `Windows 10` will be fine. All thats needed is that you have `MATLAB`

### Introduction

This application demostrates a number of phenomena, including gravity waves, barotropic instability, orographic Rossby waves, geostrophic turbulence,
tsunamis and equatorially trapped waves.

The [Shallow Water Equations are](https://en.wikipedia.org/wiki/Shallow_water_equations):

  `dh/dt + d(uh)/dx + d(vh)/dy = 0`
  
  `d(uh)/dt + d(u^2h + gh^2/2)/dx + d(uvh)/dy = h(fv - gdH/dx)`
  
  `d(vh)/dt + d(uvh)/dx + d(v^2 + gh^2/2)/dy = h(-fu - gdH/dy)`
  
  Note: `H` is the orography; a mass of some type that sits on the ocean floor. The `d` in the equations represent partial derivatives.

### Running the Model


