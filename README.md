# A-neural-network-potential-for-aluminum

Neural network potential (NNP) for aluminum, trained within the MedeA® environment and extracted for use with LAMMPS.

This repository contains a high-dimensional neural network potential (NNP) for aluminum, developed using the MedeA® software suite. The potential has been trained to accurately reproduce DFT-level energetics and forces for Al systems.

## Files

- **`Al.frc`** – MedeA force field file containing the trained NNP parameters in native MedeA format.
- **`input.nn`** – LAMMPS input script for running molecular dynamics simulations with the NNP.
- **`scaling.data`** – Scaling parameters for input/output normalization used by the neural network.
- **`weights.013.data`** – Trained weights and biases of the neural network potential.

The three files (`input.nn`, `scaling.data`, `weights.013.data`) are the core LAMMPS input files required to run the potential outside the MedeA environment.

## Citation

If you use this potential in your research, please cite the following publication:

```bibtex
@article{AKHMEROV2024113159,
title = {A neural-network potential for aluminum},
journal = {Computational Materials Science},
volume = {244},
pages = {113159},
year = {2024},
issn = {0927-0256},
doi = {https://doi.org/10.1016/j.commatsci.2024.113159},
url = {https://www.sciencedirect.com/science/article/pii/S092702562400380X},
author = {R.F. Akhmerov and I.I. Piyanzina and O.V. Nedopekin and V. Eyert},
keywords = {Machine learning, Molecular dynamics, Density functional theory, Metal, Aluminum}
