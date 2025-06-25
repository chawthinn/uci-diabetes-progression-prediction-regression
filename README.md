# Diabetes Progression Prediction

This repository contains Assignment 3 for AML2203 - Advanced Python. It uses Scikit-learn to perform linear regression on the diabetes dataset to predict disease progression. Includes EDA, preprocessing, model training, evaluation, and interpretation.

## Objective

- Apply Linear Regression using Scikit-learn
- Explore feature relationships using visualizations
- Train/test a model to predict disease progression
- Evaluate using RMSE, R², and interpret coefficients

## Files

- `scripts/AML2203_Assignment3_Chaw_916347.ipynb`: Main notebook with all code
- `final_report/AML2203_Assignment3_Chaw_916347_final_report.pdf`: Final PDF report with analysis, plots, and interpretations

## Tech Stack

* **Python 3.10+**
* **Scikit-learn** – for model building, evaluation, and cross-validation
* **Pandas** – for data manipulation
* **NumPy** – for numerical operations
* **Matplotlib** – for plotting
* **Seaborn** – for visualization
* **Statsmodels** – for Q-Q plot (goodness-of-fit analysis)

## Notebook Structure

This notebook is organized into clear sections to guide the end-to-end process of predicting diabetes progression using Linear Regression:

1. **Objective & Background**
   Brief overview of the project goals and context.

2. **Dataset Introduction**
   Summary of features available in the built-in Scikit-learn diabetes dataset.

3. **Exploratory Data Analysis (EDA)**
   Includes visual analysis to understand feature relationships and distributions.

4. **Data Preprocessing**

   * Standardizing features
   * Dropping highly correlated variables
   * Handling missing values
   * Train-test splitting (80/20)

5. **Model Building**

   * Training with `LinearRegression`
   * Applying Ridge and Lasso regularization

6. **Model Evaluation**

   * Performance metrics (MSE, RMSE, R²)
   * Visualizations: Predicted vs Actual, Residuals plot, Q-Q plot

7. **Model Interpretation**

   * Coefficient analysis
   * Feature importance discussion
   * Linear regression assumptions
   * Performance comparison (Linear, Ridge, Lasso)

8. **Report & References**
   Final insights and citation of sources used (e.g. MedlinePlus)

## Report

The final report (with all analysis, plots, and interpretations) can be found in the `final_report` folder as `AML2203_Assignment3_Chaw_916347_final_report.pdf`.
