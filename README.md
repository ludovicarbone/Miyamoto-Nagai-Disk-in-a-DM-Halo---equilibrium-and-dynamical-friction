# Dynamics of a Miyamoto-Nagai Disk in a Hernquist Halo: Equilibrium and the Effect of Three Different Perturbers.
Project for final examination of the course of the professor Massimo Dotti 'Dynamics of stellar systems' 2023-2024, Università degli Studi di Milano-Bicocca.

## Description
This project investigates a system consisting of a Miyamoto-Nagai disk embedded in a static Hernquist halo. The simulation focuses on:
- Initializing the disk's spatial coordinates using MCMC methods (position_generation_MCMC.ipynb);
- Assigning velocities based on the theoretical model and constraints (Initialization_system.ipynb);
- Analyzing the equilibrium state and the effects of perturbers with varying masses (Visualization_and_Analysis.ipynb).

## Simulation Files
Due to size constraints, the full simulation data files are not included in this repository. However, you can access them via this [Google Drive folder](https://drive.google.com/drive/folders/1HyY4uvtq2BRBCbJIa6yHzu842k-u3KG8?usp=sharing).

## Software Used
The simulation was performed using a customized version of a treecode. 
The main function was modified to include the static Hernquist potential for consistency with the system setup. For more details, refer to the [treecode documentation](https://legacy.ifa.hawaii.edu/faculty/barnes/treecode/treeguide.html).  

## Acknowledgments
The initialization of the system was developed in collaboration with [Malvina Bellotti](https://github.com/malvibellotti), whose contributions are greatly appreciated.
