# 📌 Risk-aware Pedestrian-Vehicle Interaction Simulation

This repository contains the code for the paper:  
**Risk-aware pedestrian-vehicle interaction simulation: A multi-objective evolutionary Bayesian-optimized social force model with adaptive interaction decisions**

---

## 📋 Introduction

This repository provides the source code for simulating risk-aware pedestrian-vehicle interactions based on an improved **Social Force Model (SFM)** integrated with a **decision-making module**. The simulation parameters are optimized via a **multi-objective evolutionary Bayesian optimization framework**, targeting a balance between **trajectory accuracy (ADE)** and **interaction safety realism (RPETE)**. The approach is validated on **CITR** and **DUT** datasets.

### The repository supports:
- Simulated pedestrian-vehicle interactions under varying traffic scenarios.
- A decision module that dynamically adjusts pedestrian responses based on vehicle proximity and behavior.
- Parameter optimization based on Pareto-efficient trade-offs between competing objectives.

---

## ⚙️ Dependencies

- **MATLAB R2023b** (or compatible version)
- **Python 3.8+** (for visualization, optional)
  - `numpy`
  - `matplotlib`
  - `pandas`
- **Required MATLAB Toolboxes**:
  - Global Optimization Toolbox
  - Statistics and Machine Learning Toolbox

---

## 🚀 Quick Start

1. **Clone this repository:**
```bash
git clone https://github.com/YourName/RiskAwareSFM.git
