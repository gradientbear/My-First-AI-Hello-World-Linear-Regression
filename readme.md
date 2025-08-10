# Linear Regression using Gradient Descent

This project demonstrates how the [gradient descent](https://en.wikipedia.org/wiki/Gradient_descent) algorithm can be applied to solve a [linear regression](https://en.wikipedia.org/wiki/Linear_regression) problem.  
A detailed explanation of this approach can be found in [this article](https://spin.atomicobject.com/2014/06/24/gradient-descent-linear-regression/).

---

## 📌 Overview

The goal is to fit a straight line to a set of data points by determining the optimal values for:

- **Slope (`m`)** – controls the steepness of the line.
- **Y-intercept (`b`)** – the point where the line crosses the Y-axis.

Gradient descent is used to iteratively adjust `m` and `b` to minimize the prediction error.

---

## 🛠 Requirements

- **Python** ≥ [2.6](https://www.python.org/doc/versions/)
- [NumPy](https://numpy.org/)

Install dependencies:
```bash
pip install numpy


## result

Starting gradient descent at b = 0, m = 0, error = 5565.107834483211
After 1000 iterations b = 0.08893651993741346, m = 1.4777440851894448, error = 112.61481011613473
