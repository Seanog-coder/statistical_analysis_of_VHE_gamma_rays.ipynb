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
git clone https://github.com/Seanog-coder/statistical_analysis_of_VHE_gamma_rays.git
cd statistical_analysis_of_VHE_gamma_rays.git
pip install -r requirements.txt
```
## Requirements
This project depends on the following python packages:
- numpy
- matplotlib
- scipy
- jupyter

These are included in the `requirements.txt` file for easy installation

## Usage
Lauch the notebook and run the analysis:

```bash
jupyter notebook statistical_analysis_of_VHE_gamma_rays.ipynb
```
Adjust the parameters like `lambda_param`,`alpha`, and `N` inside the notebook to explore different scenarios.

## Example Output
- Histogram of Li & Ma significance values with a normal PDF overlay.
- Significance build-up curves with different alpha ratios.
- Shapiro-wilks test results (shows normality of distribution)

## Reference
Li, T.-P., & Ma, Y.-Q. (1983). _Analysis methods for results in gamma-ray astronomy._
The Astrophysical Journal, 272, 317–324.
