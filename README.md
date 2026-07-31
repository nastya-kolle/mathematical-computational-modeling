# Mathematical & Computational Modeling — Lab Assignments

13 labs from a university course on mathematical and computational modeling: numerical methods for ODEs and PDEs, classic models from mathematical biology and physics, regression analysis, and spectral methods — all implemented in Python (NumPy/SciPy/SymPy).

## Contents

| # | Topic | Methods |
|---|---|---|
| [01](./MCM_01.ipynb) | Damped harmonic oscillator | Analytical solution, `solve_ivp` (RK45) |
| [02](./MCM_02.ipynb) | Boundary value problem (Woods-Saxon potential) | Tridiagonal (Thomas) algorithm, Runge error estimate |
| [03](./MCM_03.ipynb) | Population growth models | Verhulst (logistic) equation, Euler's method, predator-pressure model |
| [04](./MCM_04.ipynb) | Lotka-Volterra predator-prey model | System of ODEs, `solve_ivp`, phase portraits |
| [05](./MCM_05.ipynb) | "Drug vs. cancer cells" model | Linear ODE system, closed-form + numerical solution with a stopping event |
| [06](./MCM_06.ipynb) | SIR epidemic model | Euler's method |
| [07](./MCM_07.ipynb) | Regression analysis | Least squares, linear & quadratic fit, RMSE |
| [08](./MCM_08.ipynb) | Wave equation | D'Alembert's formula, mixed Dirichlet boundary problems |
| [09](./MCM_09.ipynb) | Vibrations of a square membrane | Fourier method (separation of variables) |
| [10](./MCM_10.ipynb) | Heat equation | Poisson's formula |
| [11](./MCM_11.ipynb) | Vibrations of a cylindrical membrane | Fourier-Bessel series |
| [12](./MCM_12.ipynb) | Fourier transform for solving an ODE | Green's function |
| [13](./MCM_13.ipynb) | Spectral analysis of a signal | Discrete Fourier transform (FFT) |

Each notebook is self-contained: problem statement (paraphrased, not a screenshot) → solution → plots → conclusions.

## Getting started

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
jupyter notebook
```

Notebooks are saved with all cells already executed, so plots and results render directly on GitHub — no need to run anything locally just to look through them.

## Tech stack

`numpy`, `scipy` (`solve_ivp`, `special`, `fft`, `integrate`) · `sympy` · `pandas` · `matplotlib`
