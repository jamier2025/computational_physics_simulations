# computational_physics_simulations
Theoretical &amp; computational physics showcase featuring quantum mechanics models, native LaTeX derivations, and interactive numerical solvers.
# Computational Physics & Theoretical Modeling

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/computational-physics-simulations/blob/main/main_simulations.ipynb)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A collection of computational physics models, numerical differential equation solvers, and data analysis scripts written in Python. This repository serves as super-curricular computational research exploring quantum mechanics, relativistic momentum, and non-linear physical systems.

---

## 🔬 Key Simulations & Notebooks

### 1. Quantum Light Quanta & Curve Fitting
* **Script:** `blackbody_fitting.ipynb`
* **Description:** Extracts Planck's constant ($h$) from empirical blackbody spectral radiance data using `scipy.optimize.curve_fit`. Compares continuous classical Rayleigh-Jeans failure against discrete quantum distributions.

### 2. Numerical ODE Differential Solvers
* **Script:** `chaotic_oscillators.py`
* **Description:** Utilizes `scipy.integrate.solve_ivp` (Runge-Kutta 4th/5th order) to model non-linear damped driven harmonic motion and double pendulum phase space dynamics.

### 3. Infinite Potential Well (Particle in a Box)
* **Script:** `quantum_well.py`
* **Description:** Computes stationary state wavefunctions $\psi_n(x)$ and probability density distributions $|\psi_n(x)|^2$ for bound energy levels in a 1D potential well.

### 4. Monte Carlo Photon Scattering
* **Script:** `monte_carlo_scattering.ipynb`
* **Description:** Uses probabilistic pseudo-random sampling to simulate Compton scattering cross-sections and photon transfer through matter.

---

## 📐 Governing Mathematical Models

### Planck Spectral Radiance Law
$$I(\nu, T) = \frac{2h\nu^3}{c^2} \frac{1}{e^{\frac{h\nu}{kT}} - 1}$$

### Time-Independent Schrödinger Equation (1D)
$$-\frac{\hbar^2}{2m} \frac{d^2\psi(x)}{dx^2} + V(x)\psi(x) = E\psi(x)$$

### Compton Wavelength Shift
$$\Delta \lambda = \frac{h}{m_e c} (1 - \cos\theta)$$

---

## 🛠️ Tech Stack & Requirements

* **Language:** Python 3.10+
* **Core Libraries:** `NumPy`, `SciPy`, `Matplotlib`, `SymPy`
* **Execution:** Jupyter Notebooks, Google Colab

To run locally:
```bash
git clone [https://github.com/YOUR_GITHUB_USERNAME/computational-physics-simulations.git](https://github.com/YOUR_GITHUB_USERNAME/computational-physics-simulations.git)
cd computational-physics-simulations
pip install numpy scipy matplotlib jupyter
jupyter notebook
