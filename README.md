# 🧠 Linear Regression via Single-Layer Perceptron

An interactive, dark-themed visual animation demonstrating how a **Single-Layer Perceptron** learns **Linear Regression** step-by-step using **Stochastic Gradient Descent (SGD)** and **Backpropagation**.

---

## 📌 Overview

Many beginners think of Neural Networks as complex black boxes. This project aims to bridge the gap between basic statistical models and Deep Learning by showing how a single artificial neuron (Perceptron) natively computes a simple linear equation:

$$\hat{y} = w \cdot x + b$$

By visualizing the **Forward Pass**, **Error Calculation**, and **Weight/Bias Updates (Backpropagation)** side-by-side with a scatter plot regression fit, you get an intuitive understanding of optimization algorithms.

---

## ✨ Features

- **Side-by-Side Animation:** Synchronized real-time plotting of data fitting and internal Perceptron state updates.
- **Complete Pipeline Visualization:**
  - **Forward Pass:** Computing $\hat{y} = w \cdot x + b$
  - **Error Calculation:** Residual error $e = y - \hat{y}$
  - **Backpropagation:** Parameter updates $\Delta w = \eta \cdot e \cdot x$ and $\Delta b = \eta \cdot e$
- **High-Quality Dark Theme:** Modern LinkedIn/GitHub ready graphics designed with Matplotlib.

---

## 🛠️ Requirements & Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/perceptron-linear-regression-viz.git](https://github.com/YOUR_USERNAME/perceptron-linear-regression-viz.git)
   cd perceptron-linear-regression-viz
