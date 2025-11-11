# Bachelor Thesis

<p align="center"> <img src="https://www.unibo.it/it/immagini/1_UNIBO_Ateneo_vert_pos.jpg/@@images/cc65c983-07a0-4359-add5-69104bcde471.png" width="213" height="150"> </p>

Bachelor thesis realised during an internship (March to June 2022) at the Physics and Astronomy department of the University of Bologna, supervised by Professor Elisa Ercolessi and PhD student Simone Tibaldi, on quantum algorithms for machine learning applications.

## Quantum Approximate Optimization Algorithm (QAOA) — Max-Cut

This repository contains a Python/Qiskit implementation of the **Quantum Approximate Optimization Algorithm (QAOA)** applied to the **Max-Cut** problem. It includes both simulator-based execution and real-device runs on IBM quantum hardware, as well as tools to visualize performance, parameter landscapes, and measurement statistics.

### Key Features :
- Construction of the problem Hamiltonian ($H_P$) and mixing Hamiltonian $(H_M)$ for arbitrary undirected graphs.
- Parameterized QAOA circuits with configurable depth ($p$), along with evaluation of expected cost values.
- Classical optimization of the parameters ($\beta,\gamma$), including visualizations such as 2D parameter landscapes, histograms, and convergence plots.
- Comparison between simulator results and IBM quantum hardware runs.
- Analysis of optimal parameters for ($p = 1, 2, 3$) and the corresponding cut value distributions.


