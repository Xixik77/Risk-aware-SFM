 Risk-aware Pedestrian-Vehicle Interaction Simulation
This repository contains the code for the paper:
Risk-aware pedestrian-vehicle interaction simulation: A multi-objective evolutionary Bayesian-optimized social force model with adaptive interaction decisions
Introduction
This repository provides the source code for simulating risk-aware pedestrian-vehicle interactions based on an improved Social Force Model integrated with an  decision-making module. The simulation parameters are optimized via a multi-objective evolutionary Bayesian optimization framework, targeting a balance between trajectory accuracy (ADE) and interaction safety realism (RPETE). The approach is validated on CITR and DUT datasets.

The repository supports:

Simulated pedestrian-vehicle interactions under varying traffic scenarios.

A decision module that dynamically adjusts pedestrian responses based on vehicle proximity and behavior.

Parameter optimization based on Pareto-efficient trade-offs between competing objectives.

 Dependencies
MATLAB R2023b (or compatible version)

Python 3.8+ (for visualization, optional)

numpy

matplotlib

pandas

Required MATLAB Toolboxes:

Global Optimization Toolbox

Statistics and Machine Learning Toolbox

Quick Start
Clone this repository:

bash
Copy
Edit
git clone https://github.com/YourName/RiskAwareSFM.git
Load the main MATLAB script in /src/:

main_simulation.m: runs the pedestrian-vehicle interaction simulation.

optimization_main.m: launches the evolutionary Bayesian multi-objective optimization.

Modify dataset paths in the script or replace with your own data under /data/.

Visualization (optional): use Python scripts in /visualization/ to plot trajectories and Pareto fronts.


References：
Helbing, D., & Molnár, P. (1995). Social force model for pedestrian dynamics. Physical Review E, 51(5), 4282–4286. https://doi.org/10.1103/PhysRevE.51.4282
