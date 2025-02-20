# 🚦 Traffic Flow Simulation & Analysis


## Overview

This project simulates traffic dynamics using Julia to analyze how lane count, vehicle density, and individual car speeds impact overall traffic flow. By modeling real-world behavior this simulation can provide insights into congestion patterns and optimal road conditions for smoother traffic.

## Features
  - Customizable Simulation – Adjust the number of lanes, cars, and speed distributions.
  - Realistic Vehicle Behavior – Models acceleration, braking, and lane-changing decisions.
  - Data Visualization – Plots of traffic speed, congestion, and bottlenecks.
  - Traffic Flow Analysis – Quantifies the impact of lane count and vehicle speed variance.

## Tech Stack
  - Language: Julia
  - Notebook: Jupyter
  - Libraries: DifferentialEquations.jl, Plots.jl, DataFrames.jl

## Key Findings
  - Increased lane count reduces congestion but has diminishing returns beyond a threshold.
  - Speed variance among vehicles leads to instability, causing bottlenecks.
  - Optimal traffic conditions depend on a balance of lane count, vehicle density, and speed standardization.

## Future Enhancements
  - Machine Learning Integration – Predict traffic patterns from real-world data.
  - Agent-Based Modeling – Simulate different driver personalities (aggressive vs. cautious).
