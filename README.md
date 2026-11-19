# Logistic Regression – Iris Dataset

## About

This lab focuses on implementing Logistic Regression from scratch using NumPy and the Iris dataset. It covers both binary and multiclass classification to understand how the algorithm works and how it learns to make predictions.

**Dataset:** [Iris Dataset – Kaggle](https://www.kaggle.com/datasets/uciml/iris)


## 1. Binary Logistic Regression

The first part uses two Iris species:
- Setosa (0)
- Versicolor (1)

Only two features are selected: Sepal Length and Sepal Width.

The implementation includes:
- Data filtering and label encoding
- Feature standardization
- Sigmoid function
- Binary Cross-Entropy loss
- Gradient Descent to optimize weights and bias
- Model training and accuracy evaluation
- Decision boundary visualization

## 2. Multinomial Logistic Regression

The second part uses all three Iris species and all four features.

The implementation includes:
- Label encoding and One-Hot Encoding
- Feature standardization
- Softmax function
- Categorical Cross-Entropy loss
- Gradient Descent for multiclass classification
- Model training and accuracy evaluation
- Decision region visualization

## Tools

Python · NumPy · Pandas · Matplotlib · Scikit-learn · KaggleHub

## What I Learned

Implementing both versions helped me understand the difference between binary and multiclass classification, how probabilities are calculated using Sigmoid and Softmax, and how Gradient Descent updates weights and bias to minimize the loss.
