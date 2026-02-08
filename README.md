# 3D-Lorenz-Attractor-Visualize

# AetherChaos: 3D Lorenz Attractor Visualizer 

A high-performance, zero-dependency Python tool that visualizes **deterministic chaos** using the Lorenz Equations.

## The Science
This project simulates a system of three ordinary differential equations originally developed by Edward Lorenz:

$$\frac{dx}{dt} = \sigma(y - x)$$
$$\frac{dy}{dt} = x(\rho - z) - y$$
$$\frac{dz}{dt} = xy - \beta z$$

By adjusting the **$\rho$ (Rho)** slider, you can observe how the system transitions from a steady state into the "Butterfly Effect," where the path never repeats.

## Features
- **Real-Time Physics**: Live calculation of differential equations.
- **Dynamic Trail**: A 1000-point memory that creates a glowing neon path.
- **Pure Python**: No external libraries like NumPy or Matplotlib required.
