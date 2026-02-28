# Predictive Models: Used Car Valuation 🚗

This repository demonstrates the evolution of machine learning models used to predict car prices based on engine power, age, and mileage.

## 📈 Included Models

### 1. Linear Regression
The baseline model exploring the simple linear relationship between engine power and price.

### 2. Polynomial Regression
An analysis of model complexity, demonstrating how higher-degree polynomials can lead to overfitting and why mathematical stability (Condition Number) matters.

### 3. Multiple Regression (Final Model)
**Performance: 0.76 R²**
Our most advanced model using **Multivariate Degree 2 Polynomials**. It captures the non-linear "depreciation curve" of vehicles while remaining stable for real-world use. Includes an interactive valuation widget.

## 🛠️ Key Techniques
* **6/3/2 Outlier Rule:** Systematic data cleaning.
* **Feature Scaling:** Using StandardScaler for numerical stability.
* **Residual Analysis:** Visual verification of model accuracy and error distribution.
