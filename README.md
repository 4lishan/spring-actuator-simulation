# Spring-Based Actuator Simulation for Cycle Time Reduction

This repository contains a simulation model of a spring-based actuator created using **Ansys Workbench**. The primary objective of the simulation is to evaluate the impact of the actuator on reducing cycle time by introducing energy into the system. The model specifically focuses on the behavior of a translational joint subjected to force from the actuator, with outputs including deformations and force distribution over time.

## Project Overview

In this project, a spring-based actuator was integrated into a mechanical system to demonstrate its potential in reducing cycle time by contributing energy. The simulation captures key parameters such as:
- **Total Deformations**: To observe the physical deformation of the system under the applied forces.
- **Force in X Direction**: To quantify the actuator's contribution to the system's motion, particularly at the translational joint.
- **Animation**: A visual representation of the system's behavior over time, showcasing the dynamic effects of the actuator.

## Key Features

- **Simulation Model**: Created in **Ansys Workbench**, focusing on a spring-based actuator interacting with a translational joint.
- **Deformation Analysis**: Plots showing total deformations in the system.
- **Force Distribution**: Graph illustrating the force applied to the translational joint in the X direction, highlighting the energy input from the actuator.
- **GIF Animation**: A dynamic animation to visually represent the model's behavior over time.

## Visualizations

### Deformation Plot
![Deformation Plot](deformation_plot.png)

### Force in X Direction Plot
![Force in X Direction Plot](force_x_plot.png)

### Animation
![System Animation](animation.gif)

### Results
The simulation demonstrates that the spring-based actuator contributes significant energy to the system, resulting in a reduction in cycle time. Key findings include:
The actuator's force input effectively reduces the time required to complete a cycle by applying a controlled force to the translational joint.
The total deformations of the system remain within acceptable limits, ensuring structural integrity while improving efficiency.

## Files in This Repository

- `model.wbpj`: The Ansys Workbench project file containing the simulation setup and configurations.
- `deformation_plot.png`: A plot depicting the total deformations of the system during the simulation.
- `force_x_plot.png`: A plot showing the force applied to the translational joint in the X direction, highlighting the energy input from the actuator.
- `animation.gif`: A GIF animation visualizing the movement of the system over time.

## Getting Started

To get started with this simulation, follow these steps:

### Prerequisites

- **Ansys 2022 R1**: The simulation files are compatible with Ansys Workbench. Ensure you have the software installed to open the `.wbpj` project file.
- **Compatible Viewer**: For viewing plots and animations, any standard image viewer or GIF viewer should suffice.

### Instructions

1. Clone or download this repository to your local machine.
   ```bash
   git clone https://github.com/4lishan/spring-actuator-simulation.git
2. Open the model.wbpj file in Ansys Workbench to review and interact with the simulation.
