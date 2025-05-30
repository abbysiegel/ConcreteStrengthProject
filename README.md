# Concrete Strength Prediction

This project was created for my Data Mining CSE 514 class (Spring 2025) at Washington University in St. Louis. This project applies both **custom gradient descent** and **OLS regression** to predict **concrete compressive strength** based on its components.

## 📂 Dataset

- **Source:** UCI Concrete Compressive Strength Data Set
- **Features:** Cement, Slag, Fly Ash, Water, Superplasticizer, Coarse/Fine Aggregate, Age
- **Target:** Compressive Strength (MPa)

## 📌 Objective

1. Implement and tune univariate and multivariate linear models using gradient descent
2. Analyze feature significance via OLS regression (t-tests, p-values)
3. Compare model performance and draw actionable insights

## ⚙️ Methods

- **Custom gradient descent** from scratch
- **Standardized and raw predictors** tested
- **Train/test split:** 900 training samples, 130 test samples (rows 501–630 reserved for testing)
- **Statistical analysis** with `statsmodels` OLS

