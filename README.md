`sklearn` `numpy`
## AI Algorithms in Pure Python
This repository contains implementations of core AI algorithms built using only pure Python. The goal of this project is to provide a hands-on understanding of AI mathematics and processes, without relying on external machine learning libraries like scikit-learn. Instead, we use libraries like NumPy for mathematical operations, allowing you to dive deep into the mathematical foundation of machine learning algorithms.

* `NumPy`: For numerical computations such as matrix operations, dot products, etc.
* `Pure Python`: The algorithms are implemented with basic Python constructs, demonstrating the core workings of each model.

### 1. Linear Regression
A simple algorithm used for modeling the relationship between a dependent variable and one or more independent variables.
The implementation uses Ordinary Least Squares (OLS) to find the best-fitting line to minimize the mean squared error (MSE).
#### Key Features:
Train a model to predict a continuous target variable.
Solve for weights using the normal equation.
### 2. Logistic Regression
A classification algorithm used for binary classification tasks.
Implements the sigmoid function to model the probability of class membership.
Uses gradient descent to minimize the log loss.
#### Key Features:
Classify data into one of two classes (0 or 1).
Use sigmoid activation function and cross-entropy loss for optimization.
### 3. Adaline (Adaptive Linear Neuron)
An early form of neural networks for regression and classification tasks.
Implements gradient descent to minimize the sum of squared errors.
Unlike Logistic Regression, Adaline uses the identity activation function and updates weights based on the error signal.
#### Key Features:
Implements batch gradient descent for training.
Suitable for both regression and binary classification.
