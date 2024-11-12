# Stochastic Process Simulation

## Overview
This project simulates three key stochastic processes using Python:
1. Symmetric Random Walk
2. Wiener Process (Brownian Motion)
3. Stock Price Simulation using a Brownian Motion model

The simulations illustrate the paths of these processes over time and compare the distribution of their final values to expected theoretical distributions. The project provides insights into random walk behavior, continuous Brownian motion, and stock price dynamics.

## Requirements
To install the required libraries, run:
- pip install numpy matplotlib scipy

## Code Description
Simulation of Processes:

- Symmetric Random Walk: Generates steps of +1 or -1 randomly. Cumulative sum represents the random walk's position over time.

- Wiener Process: Represents a continuous-time stochastic process. Steps are drawn from a normal distribution with mean 0 and variance proportional to the time step size.

- Stock Price Simulation: Implements a geometric Brownian motion model for stock price dynamics. Incorporates drift and volatility to model realistic stock movements.

Visualization:

- The script plots paths for each process to visualize their behavior over time.
It generates histograms of the final values of each process after the last step.
Expected normal distributions are plotted alongside histograms for comparison.

Expected Output:

- Path Plots: The first row of plots shows a subset of simulated paths for each process.
- Histograms: The second row of plots displays the distribution of the final values with an overlay of the theoretical distribution.