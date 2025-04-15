# Rotation Matrices and Direction Cosine Matrices

This project explores the mathematical foundations of rotation matrices and direction cosine matrices (DCMs) in three-dimensional space, using both numerical calculations with NumPy and symbolic mathematics with SymPy.

## Overview

The Jupyter notebook in this repository demonstrates:

- Elementary rotation matrices for rotations about principal axes (X, Y, Z)
- Composition of rotations using sequential rotation sequences
- Symbolic representation of rotation matrices with LaTeX
- Euler angles and their relation to Direction Cosine Matrices
- Common rotation sequences including:
  - Aircraft Euler Angles (3-2-1 sequence): Yaw → Pitch → Roll
  - Classical Euler Angles (3-1-3 sequence): Precession → Nutation → Spin

## Requirements

The following Python libraries are required:

- NumPy: For numerical calculations
- SymPy: For symbolic mathematics
- IPython: For display formatting with LaTeX

You can install these dependencies using pip:

```bash
pip install numpy sympy ipython
```

## Usage

Open the Jupyter notebook `rotationSequence.ipynb` to explore:

1. Mathematical definitions of elementary rotation matrices
2. Functions to compute Direction Cosine Matrices (DCMs) for arbitrary rotation sequences
3. Symbolic representations of common rotation sequences
4. Numerical examples with practical applications
