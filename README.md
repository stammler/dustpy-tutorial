# DustPy Tutorial

This repository contains tutorial material for [DustPy](https://github.com/stammler/dustpy) and [DustPyLib](https://github.com/stammler/dustpylib).

## Installation

### DustPy and DustPyLib

Installation requires a Fortran compiler accessible on your system. To install DustPy and DustPyLib use one of these commands depending on your prefered environment:

#### pip

```
pip install dustpylib
```

#### pixi

```
pixi add --pypi dustpylib
```

#### uv

```
uv pip install dustpylib
```

### RADMC-3D

The tutorial will also cover synthetic observations using [RADMC-3D](https://www.ita.uni-heidelberg.de/~dullemond/software/radmc-3d/index.php). If you want to follow this part of the tutorial, please follow these [installation instructions](https://www.ita.uni-heidelberg.de/~dullemond/software/radmc-3d/manual_radmc3d/installation.html).

### Testing the installation

The successful installation can be tested by running the notebook:

[1.1 Installation Test](/notebooks/1_preparations/1.1_installation_test.ipynb)

If this notebook runs without error, the installation was successful.