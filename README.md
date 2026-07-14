# Monte Carlo Simulation: Guangzhou Commercial Real Estate Pricing

Ornstein-Uhlenbeck (OU) process vs. Geometric Brownian Motion (GBM) comparison for modeling commercial retail property price dynamics in Guangzhou, China.

## Overview

This project uses CREIS Guangzhou monthly commercial retail price index data to calibrate two stochastic models and compare their tail risk estimates over a 24-month horizon.

## Key Results

- OU provides a more economically plausible fit under China's Three Red Lines policy framework
- GBM overestimates downside risk by approximately 5x at the 95% confidence level
- A documented 2024 Q2 sample refresh by CREIS required data filtering for valid calibration

## Built With

Python (NumPy, Pandas, Matplotlib, SciPy) in Google Colab.
