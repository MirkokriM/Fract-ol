<img src="https://github.com/MirkokriM/42_Common_Core/blob/main/README.FILE/MirkokriM_github42_Fractol.png">

Fract-ol is a project developed as part of the curriculum at the 42 coding school. It is a program that allows users to explore and visualize various fractals in real-time. This README.md provides detailed information on the project, its functionalities, and how to use it.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Fractal Types](#fractal-types)
- [Controls](#controls)
- [Features](#features)
- [Example](#example)

## Introduction

The Fract-ol 42 project aims to familiarize users with the concept of fractals and provide an interactive platform to explore different types of fractal patterns. Fractals are complex mathematical objects that exhibit self-similarity at various scales. They are visually appealing and offer unique patterns.

This program is written in C using the MiniLibX library, which provides a simple way to create graphical applications.

## Installation

To install and run Fract-ol, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/MirkokriM/Fract-ol.git
   ```

2. Navigate to the project directory:
   ```
   cd Fract-ol
   ```

3. Compile the program using the Makefile:
   ```
   make re
   ```
<p align="center">
   <img width="45%" src="https://github.com/MirkokriM/Fract-ol/blob/main/README.FILE/Fractol-make%20re.gif">
</p>

## Usage

To launch the Fract-ol program, use the following command:
```
./fractol [fractal_type] [window_resolution]
```
Replace `[fractal_type]` with the desired fractal type (e.g., mandelbrot, julia, tribrot). 
Replace `[window_resolution]` with the desired resolution(e.g, 480p, 720p, 2160p).
- If no resolution is specified, it is automatically set to 1080p.
<p align="center">
   <img src="https://github.com/MirkokriM/Fract-ol/blob/main/README.FILE/Fractol_RESANDFUNC.gif">
</p>

## Fractal Types

My Fract-ol supports the following fractal types:
- **Mandelbrot**: A classic fractal that exhibits self-similarity and infinite complexity. It is generated using the Mandelbrot set formula.
- **Julia**: A fractal similar to the Mandelbrot set, but instead of varying the initial point, it uses a fixed point throughout the visualization.
- **Tribrot**: A fractal that seems to be the fusion between the well-known Tricorn fractal and Mandelbrot fractal.

## Controls

Once the program is launched, you can use the following controls to interact with the fractal visualization:

- **Help**: Use the "H" key to bring up a small U.I for the command list and a iteration counter.
- **Navigation**: Use the arrow keys to move the fractal in different directions.
- **Zoom**: Scroll up or down to zoom in or out of the fractal.
- **Iterations**: Press the "+" or "-" key to increase or decrease the number of iterations for generating the fractal.
- **Color Schemes**: Press "X" or "C" to switch between different color schemes.
- **Reset Fractal**: Press "R" key to to reset the fractal parameters.
- **Exit**: Pres the "ESC" key or cross over the window's frame to close the window and finish the program cleanly.
- **ONLY FOR JULIA**: With a mouse click on any point of the window the fractal changes the value of the complex constant used to calculate the set, making changes to the shape of the fractal.
<p align="center">
   <img src="https://github.com/MirkokriM/Fract-ol/blob/main/README.FILE/Fractol_the.kawaii.julia.gif">
</p>

## Features

My Fract-ol provides the following features:

- Real-time rendering and navigation of fractals.
- Different color schemes to enhance visual representation.
- Dynamically adjustable maximum iteration count for generating the fractal.
- Set the fractal window resolution as an additional parameter.
- Good handling of errors due to missing or incorrect input parameters.

## Example

- Color Shift
<p align="center">
   <img src="https://github.com/MirkokriM/Fract-ol/blob/main/README.FILE/Fractol_color.shift.gif">
</p>

- Good Fractals
