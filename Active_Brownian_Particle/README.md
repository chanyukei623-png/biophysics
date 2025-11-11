**Overview**

This project simulates Active Brownian Particles (ABPs) in a 2D periodic box. The goal is to study particle motion and collective behavior in simple active matter systems.

The simulation models:

Self-propulsion of particles along their orientations

Short-range repulsive interactions (WCA potential)

Rotational diffusion of particle orientations

Periodic boundary conditions

Files

abp_simulation.py — main Python script that:

Runs the ABP simulation

Animates particle motion

Computes mean square displacement (MSD)

Computes average cluster size over time

ABP.png — animation of active particles

msd_plot.png — mean square displacement vs time

cluster_size.png — average cluster size vs time

**Requirements**

Python 3.x

Libraries: numpy, matplotlib, scipy

**How to Run**

Run the simulation:

python abp_simulation.py


The simulation will:

Animate the particles in a 2D box

Generate plots:

MSD (msd_plot.png)

Average cluster size (cluster_size.png)

**Simulation Parameters**

n_particles — Number of particles (default: 50)

box_size — Size of the simulation box (default: 20.0)

dt — Time step (default: 0.005)

n_steps — Number of simulation steps (default: 5000)

v0 — Self-propulsion speed (default: 0.3)

Dr — Rotational diffusion constant (default: 0.1)

sigma — Particle diameter (default: 1.0)

epsilon — Strength of repulsive interaction (default: 1.0)

You can modify these parameters at the top of the script to explore different regimes.

**Features**

2D ABP simulation with periodic boundaries

Short-range repulsive forces using WCA potential

Rotational diffusion of particle orientations

Animation of particle dynamics

MSD and cluster size analysis

