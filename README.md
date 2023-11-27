# AI Class Practice - Logistic, Linear Regression, and Instance-Based Learning Exercises

Author: Papagrigoriou Vasileios Savvas (vpapagr@csd.auth.gr)

## Introduction
This document outlines exercises conducted in the ML class, focusing on Logistic Regression, Linear Regression, and Instance-Based Learning. The exercises involve analyzing a diabetes dataset and a wine quality dataset using various techniques to predict outcomes and understand key features.

## Exercise 1: Logistic Regression
Detailed steps and analysis for implementing logistic regression to predict diabetes outcomes, using accuracy as the evaluation metric.

## Exercise 2: Linear Regression
Utilizing linear regression to predict blood pressure levels based on age, BMI, and pregnancy count. Evaluation is based on Mean Absolute Error (MAE).

## Exercise 3: Instance-Based Learning
### KNN Classification
- Import and preprocess the wine quality dataset.
- Perform KNN Classification to predict the type of wine.
- Experiment with different hyperparameters like `n_neighbors`, `weights`, and `p`.
- Evaluate models using accuracy scores and display results in a sorted table.
- Analyze the impact of different features on KNN performance using histograms for each wine type.
- Utilize a Decision Tree to determine feature importance.
- Test the impact of dropping the least important feature on model accuracy.

### KNN Regression
- Implement KNN Regression to predict wine quality.
- Encode categorical variables and preprocess the dataset.
- Fit models with various hyperparameters and evaluate using Mean Squared Error (MSE).

### Bonus: LDA and UMAP
- Apply Linear Discriminant Analysis (LDA) and UMAP for dimensionality reduction.
- Visualize the train and test datasets after applying LDA.
- Evaluate the performance of a KNN classifier using LDA-transformed data.
- Perform the same evaluation with UMAP-transformed data and compare the results.
