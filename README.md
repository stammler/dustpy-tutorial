# DustPy Tutorial

This repository contains tutorial material, especially Jupyter notebooks, for [DustPy](https://github.com/stammler/dustpy) and [DustPyLib](https://github.com/stammler/dustpylib).

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

This notebook prints a message if the installation was successful or if any errors occur.

## Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/stammler/dustpy-tutorial/HEAD)

If you do not want to or unable to install DustPy and/or RADMC-3D you can run these notebooks on [Binder](https://mybinder.org/).

Please be aware, that this will only let you set up the simulations, but not necessarily run them due to limited resources.

## Tutorial

The tutorial is structured as follows

### 2. Basics

* [2.1 Introduction to Simframe](/notebooks/2_basics/2.1_simframe.ipynb)
* [2.2 DustPy: Basic Usage](/notebooks/2_basics/2.2_dustpy_basics.ipynb)

### 3. Advanced Setups

* [3.1 Ice Lines](/notebooks/3_advanced/3.1_ice_lines.ipynb)
* [3.2 Planetary Gaps and Planetesimal Formation](/notebooks/3_advanced/3.2_substructure_planet_formation.ipynb)
* [3.3 Radiative Transfer Modelling](/notebooks/3_advanced/3.3_radiative_transfer.ipynb)