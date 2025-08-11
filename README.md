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
