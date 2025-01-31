# Ridge Regression and LASSO for Binary Classification

## Description

This project implements **Ridge Regression and LASSO** for binary classification on the **MNIST dataset**, specifically distinguishing between digits **'7' and '9'**. The performance of these regression models is compared against **Linear Regression**, evaluating their **convergence rate** and **classification accuracy**.

Additionally, the project includes **SGD for LASSO** and compares its solution with **Linear Regression** using the **Boston Housing Dataset**.

## Features

- **Ridge Regression (L2 Regularization):** Helps prevent overfitting by penalizing large coefficients.
- **LASSO (L1 Regularization):** Encourages sparsity by driving some coefficients to zero.
- **SGD for LASSO:** Implements stochastic gradient descent for LASSO and compares performance with linear regression.
- **Comparison with Linear Regression:** Analyzing differences in performance and convergence.
- **Binary Classification on MNIST:** Classifies digits '7' and '9'.
- **Boston Housing Dataset Regression:** Evaluates performance of LASSO with SGD vs. Linear Regression.
- **Performance Metrics:** Evaluates accuracy, loss, and convergence speed.

## Technologies Used

- Python
- Scikit-learn
- NumPy
- Matplotlib

## Installation

```bash
pip install numpy scikit-learn matplotlib
```

## Dataset

The project uses:

- **MNIST dataset:** Extracting images corresponding to the digits **'7' and '9'** to perform binary classification.
- **Boston Housing Dataset:** Evaluating LASSO with SGD and comparing it with linear regression for housing price prediction.

## Project Tasks

1. **Load and Preprocess Data:** Extract digit classes '7' and '9' from MNIST and prepare the Boston Housing dataset.
2. **Implement Ridge Regression:** Train model and evaluate performance.
3. **Implement LASSO Regression:** Train model and evaluate performance.
4. **Implement SGD for LASSO:** Apply stochastic gradient descent and compare results with linear regression.
5. **Compare with Linear Regression:** Assess accuracy and convergence.
6. **Visualize Results:** Analyze performance metrics and decision boundaries.

## Visualizations

- **Loss and Convergence Analysis:** Compare training loss over iterations.
- **Feature Importance:** Examine which features are reduced by LASSO.
- **Decision Boundaries:** Visual representation of classification regions.

## Acknowledgments

- Scikit-learn for machine learning implementations.
- MNIST dataset for digit classification research.
- Matplotlib for visualization.

