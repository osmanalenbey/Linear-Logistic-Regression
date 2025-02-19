# Linear and Logistic Regression

This repository contains an implementation of **Linear Regression** and **Logistic Regression** from scratch using Python and NumPy. The notebook provides an intuitive understanding of these fundamental machine learning algorithms, demonstrating their core principles and practical applications.

## Overview of Algorithms

### Linear Regression
Linear regression models the relationship between a dependent variable and one or more independent variables using a straight-line approximation. The algorithm minimizes the **Mean Squared Error (MSE)** by adjusting the model parameters through **Ordinary Least Squares (OLS)** or **Gradient Descent**, ensuring optimal predictions.

Key aspects:
- Hypothesis function:  $h(x) = \theta_0 + \theta_1 x $ 
- Cost function: **Mean Squared Error (MSE)**
- Optimization: **Gradient Descent** for parameter updates or **OLS** for direct solution
- Use case: Predicting continuous values (e.g., house prices, temperature)

### Logistic Regression
Logistic regression is a classification algorithm that predicts probabilities using the **Sigmoid Function**. Unlike linear regression, it is used for binary classification tasks (e.g., spam detection, disease prediction).

Key aspects:
- Hypothesis function: $h(x) = \frac{1}{1 + \exp(-\theta^T x)} $  
- Cost function: **Binary Cross-Entropy (Log Loss)**
- Optimization: **Gradient Descent** for parameter updates
- Use case: Predicting binary outcomes (e.g., spam vs. not spam)
