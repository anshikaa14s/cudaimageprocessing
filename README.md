# CUDA Image Processing: Grayscale Conversion and Blur

This project demonstrates GPU-accelerated image processing techniques using **NVIDIA CUDA and OpenCV**. It includes CUDA-based RGB-to-grayscale conversion and a customizable box blur implementation with multiple passes and optimized GPU memory usage.

## Features

- RGB to Grayscale conversion using CUDA
- Customizable Box Blur implementation using CUDA
- Multiple blur passes for stronger effects
- Parallel pixel-level processing using CUDA threads
- Efficient GPU memory usage with alternating buffers

## Prerequisites

- NVIDIA CUDA Toolkit (version 10.0 or later recommended)
- OpenCV (version 4.0 or later recommended)
- CUDA-capable NVIDIA GPU
- C++ compiler with C++11 support

## Building the Project

1. Ensure that CUDA Toolkit and OpenCV are installed.

2. Clone this repository:

```bash
git clone https://github.com/anshikaa14s/cudaimageprocessing.git
cd cudaimageprocessing