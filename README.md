
# Ship Seaworthiness Assessment Using CFD and GPU Acceleration

## Overview

This project focuses on evaluating the seaworthiness of ships through advanced **Computational Fluid Dynamics (CFD)** simulations, enhanced by **GPU acceleration**. The goal is to model the complex fluid-structure interactions between vessels and water, allowing precise predictions of **hydrodynamic forces**, **fluid flow patterns**, and **stability** under various environmental conditions.

Key elements of the project include:
- **CFD Simulations**: Assess ship behavior across multiple sea states, hull designs, and vessel speeds.
- **GPU Acceleration**: Leverage GPU power to speed up the calculations and simulations.
- **Ship Design Improvements**: Identify areas for enhancing ship designs, propulsion systems, and operational strategies.
- **Seaworthiness Evaluation**: Ensure safe, stable, and efficient vessel operation in diverse conditions.

## Features

- **Hydrodynamic Modeling**: Simulates fluid-structure interactions using CFD to predict how water and ships interact in real-world scenarios.
- **GPU Accelerated Performance**: Utilizes GPU acceleration to reduce the computational time for large and complex simulations.
- **Ship Stability & Performance Analysis**: Examines factors such as stability, resistance, and efficiency to improve ship design and operation.
- **Environmental Scenarios**: Models ship behavior across different sea states, including varying wave heights, vessel speeds, and external conditions.

## Objectives

1. Deepen understanding of ship behavior under different environmental conditions.
2. Identify design improvements in ship hulls, propulsion systems, and operational strategies.
3. Enhance the safety, stability, and performance of maritime vessels through precise CFD analysis.
4. Contribute to the development of safer, more efficient, and environmentally sustainable maritime transportation systems.

## Technologies Used

- **Computational Fluid Dynamics (CFD)**: Numerical methods to solve and analyze fluid flows.
- **GPU Acceleration**: High-performance computing to optimize CFD simulations.
- **Python / C++ / Fortran**: Core programming languages for implementing the CFD calculations.
- **OpenFOAM / ANSYS Fluent**: Tools for performing CFD simulations.
- **Docker**: Containerization for environment setup and reproducibility.

## Installation

To get started, clone this repository and follow the steps below to set up the environment and run the simulations:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ship-seaworthiness-cfd.git
   cd ship-seaworthiness-cfd
   ```

2. **Install dependencies**:
   Depending on your choice of CFD solver, ensure the following are installed:
   - OpenFOAM
   - ANSYS Fluent (if using)
   - Docker (for containerized setup)
   - GPU driver and CUDA libraries (for GPU acceleration)

3. **Run the simulation**:
   Example command for running a Docker-based simulation:
   ```bash
   docker run --gpus all -v $(pwd):/workspace your-cfd-container
   ```

4. **Configure simulations**: Modify the CFD input files located in the `input/` directory to fit the desired sea states and vessel configurations.

## Usage

- Configure the hull design, sea state, and operational parameters in the `config/` folder.
- Run the simulations via Docker or directly on your machine.
- Visualize the results using the provided scripts or tools like ParaView.

## Results

Once the simulations are completed, the output will include:
- Hydrodynamic forces
- Fluid flow visualization
- Stability analysis reports
- Performance metrics for different ship designs and conditions
