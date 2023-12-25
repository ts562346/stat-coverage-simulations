# Statistical Simulations in R

## Overview

This repository contains R code for simulating the empirical coverage of student t-confidence intervals under different conditions. The simulation investigates how changes in sample size and the number of simulations affect the accuracy of empirical coverage estimates.

## Files

- **simulation_code.R**: R script containing the simulation code.
- **README.md**: This file, providing an overview of the repository.

## Instructions

1. **Run the Simulation**: Execute the `simulation_code.R` script in your R environment.
2. **Review Results**: Examine the results of the simulation to understand the empirical coverage under various scenarios.

## Simulation Parameters

- **Sample Size (n)**: 10 (for the initial simulation) and 200 (for the second simulation).
- **Number of Simulations (Nbatch)**: 20 (initial) and 1000 (second).

## Results

- The `simulation_code.R` script generates a plot illustrating confidence intervals for each simulation batch.
- The empirical coverage is calculated and printed for each scenario.
