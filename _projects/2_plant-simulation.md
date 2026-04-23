---
layout: page
title: Plant Tissue Growth Simulation
description: Computational biology research with auxin transport modeling
img: 
importance: 2
category: research
---

Extended semicircular leaf model with auxin transport and PIN polarization for computational biology research using the Jönsson lab's Tissue Simulator.

## Overview

This project involved extending a plant tissue growth simulator to model auxin transport and cell division in leaf development. The simulation helps understand how hormonal signals guide cellular organization during plant growth.

## Tech Stack

- **C++** - Core simulation engine
- **Python** - XML scripting for model configuration
- **VirtualLeaf/Organism-Tissue Simulator** - Jönsson lab framework
- **Paraview** - 3D visualization of tissue structures
- **WSL/Ubuntu** - Development environment

## Key Components

**Cell Division Modeling**
- Implemented cell division logic based on growth thresholds
- Integrated with existing tissue mechanics

**Auxin Diffusion**
- Simulated auxin hormone transport between cells
- Debugged variable index mismatches in diffusion equations

**PIN Polarization**
- Modeled auxin efflux carrier protein distribution
- Analyzed effects on tissue patterning

**Visualization**
- Generated 3D tissue structures in Paraview
- Created time-series animations of growth dynamics

## Challenges

Debugging C++ simulation c