# Beam Deflection Analysis and Plotting

This repository contains a Python program designed to calculate and visualize the deflection of a simply supported beam subjected to a uniform distributed load (UDL). The program uses standard beam theory (Euler-Bernoulli beam theory) to calculate the deflection and slope of the beam at each point along its length.

## Project Overview
The objective of this project is to provide an easy-to-use tool for performing beam deflection analysis under a UDL. The program is capable of:
- Calculating the maximum deflection of the beam.
- Generating the deflection curve based on the beam’s material properties, geometry, and loading conditions.
- Visualizing the loading condition and deflected shape with detailed plots, where the deflection values are shown in millimeters.

This project is especially useful for students, researchers, or professionals working with structural analysis who need a quick way to understand the behavior of a beam under simple loading conditions.

## Features
- **Deflection Calculation:** The program calculates the deflection at various points along the beam due to a uniform distributed load.
- **Slope Calculation:** In addition to deflection, the slope of the beam is also calculated at each point, providing insight into the beam's bending behavior.
- **Visualization:** The program produces two plots:
    1. The beam with the UDL applied (loading condition visualization).
    2. The deflected shape of the beam, showing how the beam bends under the applied load.
- **Units:** All deflection results are displayed in **millimeters (mm)** for practical interpretation.

## Requirements
To run this project, you will need Python 3.x and the following Python libraries:
- `numpy` for numerical calculations.
- `matplotlib` for plotting graphs.
- `scipy` for solving the differential equations related to beam deflection.

Install the required dependencies by running the following command:

```bash
pip install numpy matplotlib scipy
