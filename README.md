🤖 Statistical Machine Learning: Data Analysis and Cross-Validation
This project applies various statistical machine learning techniques to a real-world dataset, focusing on model fitting, performance evaluation, and model selection using cross-validation techniques. The goal is to compare different supervised learning algorithms on the same prediction task and select the most appropriate model based on empirical validation results.

📌 Project Objectives
Perform exploratory data analysis and preprocessing

Apply multiple machine learning models: Linear Regression, Ridge, Lasso, PCR, PLS

Conduct model validation using:

K-Fold Cross Validation

Leave-One-Out Cross Validation (LOOCV)

Compare models based on prediction accuracy and bias-variance trade-off

🧠 Models Evaluated
🔹 Linear Regression
Fitted using lm()

Evaluated for overfitting, multicollinearity

🔹 Ridge Regression
Penalizes large coefficients to reduce variance

Uses glmnet with alpha = 0

🔹 Lasso Regression
Encourages sparsity for feature selection

Uses glmnet with alpha = 1

🔹 Principal Component Regression (PCR)
Performs PCA followed by linear regression

Helps with multicollinearity and dimensionality reduction

🔹 Partial Least Squares (PLS)
Similar to PCR but considers both predictors and response during decomposition

📈 Model Evaluation Techniques
10-Fold Cross-Validation: Used to assess model generalization

LOOCV: Evaluates models under high-bias, low-variance scenarios

Validation Curves: Visual comparison of test and train error vs. model complexity

📊 Key Performance Metrics
Mean Squared Error (MSE)

R-squared (R²)

Number of selected features (Lasso)

🔬 Results Summary
Lasso regression outperformed other methods in terms of interpretability and accuracy

PCR and PLS achieved competitive results but required tuning for the number of components

Cross-validation results guided model choice by balancing bias and variance

📁 Files Included
Statistical Machine Learning - Data Analysis and Cross Validation.qmd: R Quarto file with complete analysis

Scripts for model training, cross-validation, and plotting

🛠️ Technologies Used
Language: R

Libraries: caret, glmnet, pls, ggplot2, dplyr, tidymodels, boot
