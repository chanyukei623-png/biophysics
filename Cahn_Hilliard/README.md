# Cahn–Hilliard Simulation

This folder contains a Python simulation of **phase separation in binary mixtures** using the **Cahn–Hilliard equation**. The simulation models how an initially mixed system evolves over time into separated domains while conserving the total concentration.

---

## **Overview**

The simulation represents a 2D grid where each cell has a concentration value `phi`:

- `phi ≈ +1` → component A  
- `phi ≈ -1` → component B  
- `phi ≈ 0` → mixed region  

Over time, small fluctuations grow into **domains of A and B**, which coarsen to minimize interfacial energy.

---

## **Features**

- Phase separation simulation in 2D  
- Animation of concentration field  
- Adjustable parameters:
  - `epsilon` → interface thickness
  - `M` → mobility
  - `dt` → time step
  - Grid size (`Nx`, `Ny`)  
- Optional energy calculation to track free energy decrease  

---

## **Requirements**

- Python 3.x  
- Packages:
  - `numpy`
  - `matplotlib`
  - `scipy` (optional, if used for Laplacian)
  - `pillow` (for saving GIF animations)
