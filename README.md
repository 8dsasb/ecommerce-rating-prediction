# E-commerce Rating Prediction

Predicting product ratings given user and item features using linear regression.

## Overview
This project builds a regression model to predict how users rate items on an e-commerce platform. The dataset includes user demographics, product category, and price information.
- Target: numeric rating
- Model: Linear Regression
- Key metrics (from notebook runs):
  - **RMSE ≈ 1.33–1.36**
  - **MSE ≈ 1.76–1.84** (varies across runs/splits)

## Steps
1. EDA and cleaning
2. Feature encoding of categorical variables
3. Train/test split
4. Linear Regression baseline
5. Evaluation with RMSE/MSE

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Matplotlib

## Results
**Best performing Model**: Model C

**Worst performing Model**: Model B

**Highest MSE**: Approximately 1.80 (Model B)

**Highest RMSE**: Approximately 1.35 (Model B)

**Lowest MSE**: Approximately 1.72 (Model C)

**Lowest RMSE**: Approximately 1.30 (Model C)

- Baseline Linear Regression reaches RMSE ≈ **1.33–1.36** on the test split(s)
- Errors suggest nonlinearity and interactions between price/category/user features
  <img width="737" height="596" alt="image" src="https://github.com/user-attachments/assets/1a6ee207-7986-4889-932d-3e9faf9eaf97" />

## Future Improvements
- Add user-item interaction features
- Try advanced regression models (Ridge, Random Forest)
- Perform feature importance analysis
