# Active Brownian Particles (ABP) Simulation

This folder contains a Python simulation of **Active Brownian Particles (ABPs)** in 2D. The simulation models self-propelled particles moving in a confined box, interacting through simple repulsive forces, and exhibiting collective behavior.

---

## **Overview**

Active Brownian Particles are **self-propelled particles** that move in a medium and change direction due to rotational diffusion:

- Each particle has a position `(x, y)` and an orientation angle `theta`.  
- Particles move with a constant self-propulsion speed `v0`.  
- Orientation changes due to **rotational noise**.  
- Interactions are modeled with **short-range repulsion** to prevent overlap.  

The simulation demonstrates **emerging collective phenomena** such as clustering, swarming, and active diffusion.

---

## **Features**

- 2D simulation of self-propelled particles  
- Periodic boundary conditions  
- Adjustable parameters:
  - `N` → number of particles
  - `v0` → self-propulsion speed
  - `D_r` → rotational diffusion coefficient
  - `dt` → time step
  - `box_size` → size of the simulation box  
- Real-time visualization using Matplotlib  
- Optionally save animation as GIF

---

## **Requirements**

- Python 3.x  
- Packages:
  - `numpy`
  - `matplotlib`
  - `pillow` (for saving GIF animations)
