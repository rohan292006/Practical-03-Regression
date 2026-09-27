# Practical Assignment 03 – Performance Evaluation of Regression Model

## Overview

This practical implements and evaluates regression models for a real-world continuous prediction problem using the Diabetes dataset available through Scikit-learn.

The practical includes:

* Linear Regression
* Ridge Regression
* Polynomial Regression
* Gradient Descent Linear Regression implemented from scratch
* MAE, MSE, RMSE and R² evaluation
* Actual vs Predicted visualization
* Gradient Descent convergence analysis

## Dataset

The Scikit-learn Diabetes dataset is used for the experiment.

* Samples: 442
* Features: 10
* Target: Continuous numerical value

## Models Implemented

### 1. Linear Regression

Used as the baseline regression model for predicting the continuous target variable.

### 2. Ridge Regression

Linear Regression with L2 regularization to control coefficient magnitude.

### 3. Polynomial Regression

Degree-2 polynomial features are used to model possible nonlinear relationships.

### 4. Gradient Descent Linear Regression

Gradient Descent is implemented from scratch by calculating gradients and iteratively updating weights and bias.

## Evaluation Metrics

The following metrics are used:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Gradient Descent Configuration

* Learning Rate: 0.03
* Epochs: 5000
* Feature Scaling: StandardScaler

## Repository Contents

```text
Practical-03-Regression/
│
├── Practical_03_Regression.ipynb
├── README.md
├── requirements.txt
└── screenshots/
```

## Tools and Technologies

* Python
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

## How to Run

1. Open `Practical_03_Regression.ipynb`.
2. Open the notebook in Google Colab.
3. Run the cells sequentially.
4. Observe the regression model metrics.
5. Observe the Gradient Descent convergence graph.
6. Compare the performance of the implemented models.

## Author

**Rohan Gawade**

B.Tech. Computer Engineering

MIT Academy of Engineering
