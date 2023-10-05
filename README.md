# Daily Conversion Rate Simulation Tool

## Introduction
This Jupyter notebook provides a tool to simulate and visualize daily conversion rates. By adjusting parameters like the target conversion rate, number of simulations, visitors per day, and total days, users can generate and inspect simulated data. The tool also allows users to view individual simulations and confidence intervals around the target conversion rate.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/erikmalk/Daily_Conversion_Rate_Simulation/HEAD?urlpath=https%3A%2F%2Fgithub.com%2Ferikmalk%2FDaily_Conversion_Rate_Simulation%2Fblob%2Fmain%2Fdaily_conversion_rate_simulation.ipynb)

## Dependencies
- numpy
- matplotlib
- ipywidgets

## Features

### `plot_simulation_data` Function
This function visualizes the simulated conversion rates. It displays:
- The sampled daily average conversion rate.
- The selected simulation's conversion rate.
- The theoretical target conversion rate.
- Confidence intervals (both 68% and 95%) around the theoretical target conversion rate.

### `generate_data` Function
Generates simulated conversion rate data based on the provided parameters. It initializes and populates a 3D array representing visitor data for each day, simulation, and visitor. This function also displays an interactive UI for selecting individual simulations.

### Interactive UI Elements
Users can adjust the following parameters using sliders:
- Number of simulations.
- Visitors per day.
- Target conversion rate.
- Total days for the simulation.
- Random seed for reproducibility.

## Usage
1. Adjust the desired parameters using the provided sliders.
2. Click the "Run Simulations" button to generate the data.
3. Use the "selected_simulation" slider to view individual simulations on the graph.

---

**Note:** Ensure all dependencies are installed and the kernel is restarted before running the notebook.
