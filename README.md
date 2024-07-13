[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Poetry](https://img.shields.io/endpoint?url=https://python-poetry.org/badge/v0.json)](https://python-poetry.org/)

# Gaussian Process

## Dependency

- [python](https://www.python.org/)
  - version 3.10 or higher is recommended.

- [poetry](https://python-poetry.org/)
  - seting up python environment easily and safely.
  - only `numpy`, `matplotlib`, `notebook` are needed to run all scripts in this repository.

## Setup
```sh
git clone https://github.com/MizuhoAOKI/gaussian_process.git
cd gaussian_process
poetry install
```

## Usage

### Gaussian Process Regression

```sh
cd gaussian_process
poetry run jupyter notebook notebooks/gp_regression_1d.ipynb
```

<img src="./media/gpr_1d.png" width="500px" alt="gaussian process regression (1 dim)">


```sh
cd gaussian_process
poetry run jupyter notebook notebooks/gp_regression_2d.ipynb
```
<img src="./media/gpr_2d_prediction.png" width="500px" alt="gaussian process regression (2 dim)">


### Bayesian Optimization

```sh
cd gaussian_process
poetry run jupyter notebook notebooks/bayesian_optimization_1d.ipynb
```

https://github.com/MizuhoAOKI/gaussian_process/assets/63337525/36b2d534-8d9f-4a5e-b26d-dc41e0032590
