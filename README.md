# Definite & Indefinite Integral Calculator

This is a Python-based GUI application for calculating both definite and indefinite integrals using multiple numerical and symbolic methods. The app is built with `Tkinter` for the GUI and supports several integration techniques like:

- Gauss-Legendre Quadrature (`torchquad`)
- Monte Carlo Integration (`torchquad`)
- Scipy's `quad` method (Use for `-inf, inf` bounds of the integral)
- SymPy's Symbolic Integration

---

## Features

- Calculate definite integrals with custom bounds.
- Calculate symbolic indefinite integrals.
- Supports infinite bounds (`-inf, inf`).
- User-friendly GUI.
- Safe parsing of mathematical functions.
---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/integral-calculator.git
cd integral-calculator
