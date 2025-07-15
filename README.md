 Risk-aware Pedestrian-Vehicle Interaction Simulation
  Overview
This repository implements a risk-aware pedestrian-vehicle interaction simulation framework, driven by an Improved Social Force Model (SFM) integrated with:

An Adaptive Decision Module to dynamically adjust pedestrian responses.

A Hesitation Model for uncertain crossing scenarios.

A Multi-objective Evolutionary Bayesian Optimization (EBO) to calibrate SFM parameters for balancing accuracy and safety.

The optimization objectives include:

ADE: Average Displacement Error (trajectory accuracy)

RPETE: Relative Post-Encroachment Time Error (interaction safety)
