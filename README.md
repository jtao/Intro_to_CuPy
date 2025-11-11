# Practical GPU Computing with CuPy

## Overview

This repository contains short course materials for **Practical GPU Computing with CuPy**, presented by Jian Tao (Texas A\&M University) on November 11, 2025. The materials guide participants through using CuPy—a GPU-accelerated array library compatible with NumPy/SciPy—for scientific computing, prototyping, and optimization tasks.[^1]

## Course Topics

- CuPy Overview and Philosophy
- Setting up and running CuPy on the ACES HPC system
- Core CuPy operations: arrays, memory management, ufuncs
- Scientific computing with GPU-accelerated libraries
- Sparse and dense linear algebra using CuPy
- Advanced GPU programming, including kernel fusion and concurrency
- 2D convolution pipeline case study
- Tips for migrating NumPy code to CuPy[^1]


## Getting Started

### Prerequisites

- NVIDIA GPU (CUDA Compute Capability 3.5+) or AMD GPU (ROCm support)
- CUDA Toolkit (11.x/12.x) or ROCm runtime
- Python 3.8+
- Matching CUDA/ROCm drivers as per CuPy's installation matrix[^1]


### Installation

Install CuPy using pip:

```bash
pip install cupy
```

For detailed instructions and compatible versions, visit [CuPy's official documentation](https://docs.cupy.dev/en/stable/install.html).

### Running Examples

Sample scripts are provided in this repository. To run them:

```bash
python example_script.py
```

See the accompanying PDF for step-by-step guides to running code both locally and on ACES (Texas A\&M's Accelerating Computing for Emerging Sciences).[^1]

### ACES HPC Guide

- Access the portal: https://portal-aces.hprc.tamu.edu
- Load modules:

```bash
module purge
module load GCC/12.3.0 OpenMPI/4.1.5 CuPy/13.0.0-CUDA-12.1.1
```

- Submit jobs via Slurm using provided submission scripts.


## Resources \& Support

- [ACES User Guide](https://hprc.tamu.edu/kb/User-Guides/ACES)
- General support: helphprc@tamu.edu
- YouTube channel: [Texas A\&M HPRC](https://www.youtube.com/texasamhrpc)[^1]


## License

See the LICENSE file for reuse and distribution terms, or contact the author for more information.

## Author

- **Jian Tao**
College of Performance Visualization \& Fine Arts,
Institute of Data Science,
Texas A\&M University
College Station, TX

***

Feel free to customize and add links to your scripts, datasets, or supplementary materials!

<div align="center">⁂</div>

[^1]: Intro_to_CuPy.pdf

