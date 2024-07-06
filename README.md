## Live Website Here
(Under dist Folder... However some models may not load due to the Glitch's new security policies)

https://mire-elderly-meadowlark.glitch.me/dist/

# Single Slit Interference Simulation

This repository contains the code for a Single Slit Interference Simulation aimed at making it easier for students to learn this topic in physics. The simulation uses ThreeJS, WebGL, and other technologies to create an interactive and educational experience.

## Table of Contents

- [Introduction](#introduction)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Performance Optimization](#performance-optimization)
- [Future Work](#future-work)
- [References](#references)

## Introduction

The Single Slit Interference Simulation project aims to provide an interactive tool for students to learn about single slit interference in physics. The simulation visualizes the interference pattern produced by light passing through a single slit, allowing users to adjust various parameters and observe the resulting changes in real-time.

## Key Features

1. **3D Visualization**: Utilizes ThreeJS to create a 3D scene with interactive elements.
2. **Custom Shaders**: Uses WebGL shaders to render the interference pattern dynamically.
3. **Responsive UI**: Implements a user-friendly interface using Tweakpane for real-time parameter adjustments.
4. **Preset System**: Allows users to save and load different setups to facilitate teaching and experimentation.
5. **Detailed Output**: Displays diagrams, graphs, numerical data, and notes about the state of the experiment.
6. **Compatibility**: Runs on all major browsers but is not supported on mobile devices.
7. 
![Screenshot 2024-07-06 at 7 29 27 PM](https://github.com/SparkleButt747/light_interference_simulation/assets/36875086/5d801586-b1df-4406-9375-ff881945245d)
![Screenshot 2024-07-06 at 7 30 18 PM](https://github.com/SparkleButt747/light_interference_simulation/assets/36875086/afcbd8ef-d614-4d9d-b0f9-85416db09b48)
![Screenshot 2024-07-06 at 7 30 35 PM](https://github.com/SparkleButt747/light_interference_simulation/assets/36875086/cc05ae48-3593-417d-aac7-3e40a07f50f7)


## Technologies Used

- **ThreeJS**: A cross-browser JavaScript library and API used to create and display animated 3D graphics in a web browser.
- **WebGL**: A JavaScript API for rendering high-performance interactive 3D and 2D graphics within any compatible web browser.
- **Tweakpane**: A compact pane library for fine-tuning parameters and monitoring value changes in real-time.
- **GSAP**: A robust JavaScript library for high-performance animations.

## Performance Optimization

The simulation includes several performance optimizations to ensure smooth operation across different devices:

2D Merge Sort: Optimizes the sorting of 3D coordinates of laser haze particles.
2D Exponential Search: Splits arrays at specific positions to optimize particle rendering.
Dynamic Programming: Reduces CPU usage by dynamically storing and updating particle positions.

## Future Work

Future enhancements to the project may include:

Adding support for mobile devices.
Implementing more complex simulations, such as double-slit interference.
Improving the preset system to allow for more customization.
Enhancing the user interface for better usability and accessibility.

## References

Three.js Documentation: https://threejs.org/docs/
WebGL Fundamentals: https://webglfundamentals.org/
Tweakpane Documentation: https://cocopon.github.io/tweakpane/
GSAP Documentation: https://greensock.com/docs/
