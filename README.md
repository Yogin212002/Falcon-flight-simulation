# Falcon-flight-simulation
Falcon Dive and brake simulation 

This project models and simulates the dynamics of a falcon during braking and diving manoeuvres using MATLAB and Simulink. The goal is to analyze the aerodynamic and kinematic behaviour under different flight conditions.

## Contents

- `Falcon_brake_simulation.slx`: Simulink model simulating the Falcon's behaviour during a braking manoeuvre.
- `Falcon_dive_simulation.slx`: Simulink model simulating the falcon's dive flight dynamics.
- `Falconparameters.mat`: Contains parameter values used in the simulations (mass, drag coefficients, etc.).
- `Falconparameters.mlx`: MATLAB Live Script that initialises and describes the simulation parameters.

## Requirements

- MATLAB R2023a or later
- Simulink
- Aerospace Blockset (optional, if advanced flight dynamics blocks are used)

## Getting Started

1. Open MATLAB and set the current folder to the directory containing these files.
2. Run `Falconparameters.mlx` to load the workspace with the required parameters.
3. Open either simulation model (`.slx`) depending on the analysis:
   - `Falcon_brake_simulation.slx` for braking dynamics
   - `Falcon_dive_simulation.slx` for dive analysis
4. Click **Run** in Simulink to simulate.
5. Analyse results using scopes, logged data, or further post-processing in MATLAB.

## Parameters

Simulation parameters are defined in `Falconparameters.mlx` and saved to `Falconparameters.mat`. Key parameters include:
- **Mass** of the falcon
- **Wing area**
- **Drag coefficient**
- **Initial velocity and altitude**
- **Gravitational acceleration**

## Applications

- Bio-inspired flight dynamics research
- Control system development for aerial robots
- Educational use in biomechanics or aerospace engineering

## License

This project is provided for educational and research purposes. Please cite appropriately if used in academic work.
