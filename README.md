# Numerical Modeling Simulation: Heat Diffusion & Stability Analysis

## 🚀 Overview
This project focuses on simulating heat diffusion in a 1D system using numerical methods.  
The goal is to understand how temperature evolves over time and analyze the stability of the simulation under different computational conditions.

---

## 🧠 Concept

Heat diffusion is a physical process where heat flows from high temperature regions to low temperature regions.

This project uses:
- Finite Difference Method (FDM)
- Time-stepping simulation
- Grid-based discretization

Instead of solving equations analytically, we approximate the solution step-by-step using Python.

---

## ⚙️ Methodology

1. Divide the system into small discrete points (grid)
2. Initialize temperature distribution
3. Apply numerical update rule at each time step
4. Repeat for multiple time steps
5. Visualize temperature evolution

---

## 📐 Mathematical Model

We simulate the 1D heat equation:

∂T/∂t = α ∂²T/∂x²

Where:
- T = Temperature
- α = Thermal diffusivity

---

## 💻 Technologies Used

- Python
- NumPy
- SciPy
- Matplotlib

---

## 📊 Features

- 🔥 Heat diffusion simulation over time
- 📈 Temperature vs time visualization
- 📉 Stability analysis by varying time step (dt)
- ⚡ Efficient numerical computation using NumPy

---

## ⚡ Stability Analysis

The simulation demonstrates how:
- Small time step → Stable results
- Large time step → Unstable / inaccurate results

This highlights the importance of numerical stability in simulations.

---

## 📸 Output

- Temperature evolution graph
- Heat distribution over time
- Stability comparison plots

---

## 📁 Project Structure

