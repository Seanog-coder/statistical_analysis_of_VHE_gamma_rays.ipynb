# Statistical Analysis of VHE Gamma Rays

This project implements a statistical framework for analyzing very-high-energy (VHE) gamma-ray observations using Monte Carlo simulations.  
It models on-source and off-source event counts as Poisson processes, applying the Li & Ma (1983) significance formula (Equation 17) to evaluate detection significance in gamma-ray astronomy.

## Features
- Simulation of large event datasets (up to \(10^8\) samples) for realistic statistical testing.
- Calculation of detection significance for varying observation times (α ratios) and event rates.
- Visual comparison of simulated significance distributions with the standard normal curve.
- Statistical normality testing (Shapiro–Wilk).
- Plots showing significance build-up over time and dependence on observational parameters.

## Installation
Clone the repository and install the required Python packages:

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
pip install -r requirements.txt
