# MSCS_634 Lab 4: Regression Analysis using Diabetes Dataset

## Overview

This lab explores different regression techniques using the Diabetes dataset from scikit-learn. The purpose of the lab is to understand how various regression models perform and how regularization methods help reduce overfitting.

## Models Implemented

- Simple Linear Regression
- Multiple Regression
- Polynomial Regression (Degree 2 and Degree 3)
- Ridge Regression
- Lasso Regression

## Dataset

The Diabetes dataset from sklearn.datasets was used. The dataset contains several health measurements that are used to predict disease progression.

## Evaluation Metrics

The following metrics were used:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

## Visualizations

The following visualizations were created:

- Simple Linear Regression plot
- Actual vs Predicted plot for Multiple Regression
- Polynomial Regression plot
- Ridge Regression prediction plot
- Lasso Regression prediction plot
- Side-by-side comparison plots

## Key Findings

- Multiple Regression achieved better prediction accuracy than Simple Linear Regression.
- Polynomial Regression improved flexibility but higher degrees may cause overfitting.
- Ridge Regression reduced coefficient magnitude and improved generalization.
- Lasso Regression simplified the model by reducing less important feature effects.
- Regularization techniques help control overfitting and improve model stability.

## Challenges Faced

- Selecting suitable polynomial degree values.
- Understanding the effects of regularization parameters.
- Comparing model performance using multiple evaluation metrics.

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Conclusion

This lab demonstrated how different regression models behave on the same dataset. Multiple Regression provided strong performance, while Ridge and Lasso regression showed the importance of regularization in controlling overfitting and improving prediction quality.
