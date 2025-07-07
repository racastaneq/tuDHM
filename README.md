# tuDHM – Telecentric Uniform Digital Holographic Microscopy

tuDHM is a collection of MATLAB and Python scripts developed for phase compensation in off-axis Digital Holographic Microscopy (DHM) under telecentric uniform configurations. The compensation is achieved through heuristic optimization of a custom cost function, enabling more accurate and robust phase retrieval from digital holograms.

## Overview
In off-axis DHM, the reconstruction of the object phase requires isolating and demodulating the +1 diffraction order in the Fourier domain. The tuDHM scripts go one step further by optimizing a digital reference wave that minimizes phase artifacts caused by misalignment, aberrations, or residual carrier fringes.

This framework is especially useful for high-precision phase imaging, such as in biological or microfluidic samples.

## Features
  - Phase compensation based on synthetic reference wave optimization
  - Heuristic optimization using custom cost functions
  - Compatible with off-axis holograms in telecentric configurations
  - MATLAB and Python implementations available

## Requirements
For MATLAB:
  - MATLAB R2020a or newer
  - Image Processing Toolbox
  - Optimization Toolbox (for particleswarm, fminsearch, etc.)

For Python:
  - Python 3.8 or newer
  - NumPy, SciPy, OpenCV, Matplotlib
  - Optional: pyDHM, skimage

## More Information
For detailed documentation, sample data, and full implementation details, please visit:
👉 https://oirl.github.io/tuDHM/
