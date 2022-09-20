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

1. Create a directory where the project will be placed/cloned to.
2. $ git clone https://github.com/MRLintern/Shallow_Water_Equations.git
3. Type `matlab` in a terminal to start in the directory in which the project resides.
4. Click on `shallow water model.m` and then click on the run button; top of interface.
5. Once the program stops running, click on `animate.m` and then run the script as you did in the previous step to view the results.

### Models

Different models can be created for different Oceanographic/Atomospheric scenarios.

1. Gravity Waves

* orography = FLAT
* initial conditions = GAUSSIAN BLOB
* initially geostrophic = false

2. 
