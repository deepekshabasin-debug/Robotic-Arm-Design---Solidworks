# Articulated Robotic Arm CAD Model

A multi-axis articulated robotic arm assembly designed and modeled in SOLIDWORKS, featuring custom part modeling, hierarchical link structuring, and precise kinematic assembly mates.

## Overview
This project models an industrial-style robotic manipulator, breaking down the mechanical structure into individual links, joints, and a stable base. It serves as a practical demonstration of 3D CAD modeling, assembly hierarchy management, and mechanical constraint setup.

## Project Structure
* **`base`**: The foundational stationary platform that anchors the entire assembly.
* **`Link1` to `Link4`**: Individual articulated segments forming the kinematic chain, allowing sequential rotation and movement.
* **`Assem1.sldasm`**: The main top-level assembly file integrating all components with proper mates and constraints.

## Features
* **Custom Part Modeling**: Each component is individually designed with attention to structural proportions and mechanical realism.
* **Kinematic Assembly Mates**: Utilizes standard and advanced SOLIDWORKS mates to define proper degrees of freedom and joint alignment.
* **Hierarchical Tree**: Organized parent-child component dependencies for clean assembly management.

## Usage
1. Clone this repository or download the project files.
2. Open SOLIDWORKS and load the main assembly file (`Assem1.sldasm`).
3. Expand the feature tree to inspect individual part files and review the applied mates.
4.
