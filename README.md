# 2D Lid-Driven Cavity LBM Simulation

## Overview
This repository contains a Python implementation of a 2D Lid-Driven Cavity fluid flow simulation using the **Lattice Boltzmann Method (LBM)**. It models fluid circulating in a square cavity where the top wall (lid) moves at a constant velocity, while the other three walls remain stationary. 

The simulation utilizes the **D2Q9** lattice model (2 dimensions, 9 discrete velocities) alongside the single-relaxation-time **BGK** (Bhatnagar-Gross-Krook) collision operator.

## Features
* **D2Q9 Lattice:** Standard 9-directional velocity streaming.
* **BGK Collision Operator:** Approximates the collision step for fluid relaxation toward equilibrium.
* **Boundary Conditions:** Standard bounce-back for the stationary left, right, and bottom walls and prescribed equilibrium velocity boundary for the moving top lid.
* **Visualization:** Generates a contour plot of the final velocity magnitude field using Matplotlib.
