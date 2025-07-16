# 📌 Risk-aware Pedestrian-Vehicle Interaction Simulation

This repository contains the code for the paper:  
**Risk-aware pedestrian-vehicle interaction simulation: A multi-objective evolutionary Bayesian-optimized social force model with adaptive interaction decisions**

---

## 📋 Introduction

This repository provides the source code for simulating risk-aware pedestrian-vehicle interactions based on a Risk-aware **Social Force Model ** integrated with a **decision-making module**. The simulation parameters are optimized via a **multi-objective evolutionary Bayesian optimization framework**, targeting a balance between **trajectory accuracy (ADE)** and **interaction accuracy (RPETE)**. The approach is validated on **CITR** and **DUT** datasets.

### The repository supports:
- Simulated pedestrian-vehicle interactions under varying traffic scenarios.
- A decision module that dynamically adjusts pedestrian responses based on vehicle proximity and behavior.
- Parameter optimization based on Pareto-efficient trade-offs between competing objectives.

---

## ⚙️ Dependencies

- **MATLAB R2023b** (or compatible version)
- **Python 3.8+** (optional for visualization)
  - `numpy`
  - `matplotlib`
  - `pandas`
  - `openpyxl` (for reading Excel files)
- **Required MATLAB Toolboxes:**
  - Global Optimization Toolbox
  - Statistics and Machine Learning Toolbox

---

## 🗂 Project Structure
```bash
.
├── core_social_force_module/   # Sub-modules for social force computation, decision-making, etc.
├── optimization/               # Parameter optimization code
├── visualization/              # Visualization scripts (Python)
├── utils/                      # Utility functions for geometric computations and scene configuration
├── main_simulation.m           # Main simulation entry
├── README.md
---

##🤝 Contributing to this project

We welcome and encourage contributions to this project! Whether it's reporting bugs, suggesting new features, or improving existing functionality, your input is highly valuable. You can open an issue on our [GitHub Issues](https://github.com/Xixik77/Risk-aware-SFM) page to share feedback or raise problems.

If you'd like to contribute directly, feel free to fork this repository and submit a pull request. Be sure to include necessary tests, comments, and documentation with your code changes.

We also recommend following best practices for version control and keeping changes consistent with the project's structure.

---
## 📄 License

Distributed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

## 🙏 Acknowledgements

- This project is developed based on our previous work on social force modeling and pedestrian-vehicle interaction simulation.
- The optimization framework design was inspired by the principles of evolutionary Bayesian optimization in multi-objective scenarios.
- Some visualization components were adapted from open-source Python visualization tools.
