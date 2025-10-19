# Kite Qubit, Transmon, and Fluxonium Simulations

This repository contains Python simulations and visualizations of several superconducting qubit types:

- **Transmon qubit** — simulated in the charge/tunneling basis  
- **Fluxonium qubit** — simulated in the phase/momentum basis  
- **KITE qubit** — simulated at different external flux bias points (`θ_ext = π` and `θ_ext = 0`)

The simulations are implemented using [QuTiP](http://qutip.org/), NumPy, SciPy, and Matplotlib.

## Features
- Compute energy spectra for varying external parameters (gate charge, external flux)
- Plot energy levels and differences relative to the ground state
- Visualize wavefunctions and potential energy profiles
- Parameterized Hamiltonians for Transmon, Fluxonium, and KITE circuits

## Requirements
- Python 3.8+
- [QuTiP](http://qutip.org/)
- NumPy
- SciPy
- Matplotlib

## Project Overview

The project focussed on reproducing and analysing the energy behaviour of superconducting qubit architectures - particularly the KITE, Transmon, and Fluxonium qubits - through numerical Hamiltonian modelling and quantum simulation. This project explored how variations in circuit parameters influenced the energy spectra and phase dynamics of the quantum system. This is visualised by the Python and Qutip simulations provided in this repository.


## Connection to Classical Electrical Engineering

Although the focus of this project was primarily on quantum systems, its foundation lies in classical circuit analysis, which was required to understand the behaviour of Josephson junction-based circuits. The Hamiltonians implemented in this project were first derived by performing classical circuit analysis using Kirchhoff's laws and Lagrangian mechanics. The classical framework was evolved into a quantum system by incorporating quantum operators such as position and momentum.



