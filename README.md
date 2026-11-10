
# Stochastic Simulations and Particle Transport

**TMA4320 – Introduction to Scientific Computation | NTNU**

## Overview

Academic project exploring stochastic modelling and numerical simulations of particle transport, inspired by the movement of molecular motor proteins in biological systems.

The project uses random walk simulations to investigate how particles move through different potential landscapes, and how interactions between particles influence their collective transport.

The simulations are based on a flashing ratchet model, where particles alternate between two potential energy landscapes.

## Technologies

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook
- Monte Carlo Simulation
- Stochastic Modelling
- Scientific Computing

## Project Components

### 1. Random Walk Simulations

Implemented one-dimensional random walk simulations to investigate particle diffusion under different potential energy landscapes.

The work included:
- Simulating stochastic particle movements
- Calculating transition probabilities
- Comparing constant and linear potentials
- Investigating the effects of temperature
- Introducing hard-core repulsion to prevent particle overlap
- Analysing particle distributions

### 2. Flashing Ratchet Model

Implemented a simplified model of molecular motor transport using two alternating potential energy landscapes.

The work included:
- Constructing periodic sawtooth potentials
- Simulating particle motion between energy states
- Applying periodic boundary conditions
- Calculating normalized particle currents
- Investigating how potential asymmetry affects transport direction
- Analysing the influence of switching periods

### 3. Numerical and Analytical Comparison

Compared simulated particle currents with analytical predictions based on the diffusion equation.

The work included:
- Evaluating analytical expressions for particle current
- Comparing numerical and theoretical results
- Investigating the effects of temperature and model parameters
- Examining limitations of analytical approximations

### 4. Interacting Particle Systems

Extended the simulations to include interactions between particles through hard-core exclusion.

The work included:
- Implementing collision constraints
- Simulating particles with finite size
- Tracking particle trajectories over time
- Investigating the effects of particle density
- Analysing how switching periods influence collective transport
- Comparing simulated behaviour with published research

## Key Learning Outcomes

- Implementing stochastic simulations in Python
- Applying probability theory to physical systems
- Developing numerical models with particle interactions
- Working with periodic boundary conditions
- Comparing analytical and numerical solutions
- Analysing simulation results through data visualization
- Investigating how model parameters affect collective behaviour

## Project Structure

- `all_kode.ipynb` – Python implementations, simulations, visualizations, and analysis

## Academic Context

Completed as part of TMA4320 – Introduction to Scientific Computation at the Norwegian University of Science and Technology (NTNU).

The project combines probability theory, statistical physics, numerical methods, and scientific programming to model stochastic particle transport in biological systems.
