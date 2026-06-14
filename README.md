# FlatSkyLab
FlatSkyLab is a Python package for generating fast, high-resolution flat-sky CMB simulations and calculating power spectra.
## https://flatskylab.readthedocs.io/en/latest/index.html
---
## Overview
FlatSkyLab provides tools for estimating the power spectrum of flatsky maps and for generating correlated realisations of both flatsky maps and time‑ordered data (TODs). It is designed to support simulation, analysis, and experimentation within the flatsky approximation, offering a flexible environment for cosmological and signal‑processing workflows.

---
## Installation
* #### `pip install .`
* To clean and reinstall:
  * `pip uninstall FlatSkyLab` and then `pip install .`

---
## Requirements
* `pyparsing>=2.0.2`, `camb>=1.5`
* Also, the standard python packages like `numpy`, `scipy`, `matplotlib`, ++

---
## Examples
* Check the [examples](https://github.com/sriniraghunathan/FlatSkyLab/tree/main/examples) folder
	*  [`make_corr_map_realisations.ipynb`](https://github.com/sriniraghunathan/FlatSkyLab/blob/main/examples/make_corr_map_realisations.ipynb): Correalted simulations of flatsky maps across multiple frequency bands.
 	*  [`make_corr_tod_realisations.ipynb`](https://github.com/sriniraghunathan/FlatSkyLab/blob/main/examples/make_corr_tod_realisations.ipynb): Correalted simulations of TOD across multiple detectors.
