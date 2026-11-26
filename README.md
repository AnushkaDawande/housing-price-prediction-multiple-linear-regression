# Housing Price Prediction Using Multiple Linear Regression

## Project Overview
This project focuses on predicting house prices using Multiple Linear Regression. It explores the relationship between different numerical housing features and their influence on house prices.

## Dataset
- **Dataset:** Housing Prices Dataset
- **File:** `Housing.csv`
- **Original Records:** 545
- **Records After Cleaning:** 544
- **Target Variable:** `price`

## Features Used
The following five numerical features were selected:
- Area
- Bedrooms
- Bathrooms
- Stories
- Parking

## Work Completed
1. Dataset loading and inspection
2. Checking dataset shape and data types
3. Missing value and duplicate analysis
4. Data cleaning and preprocessing
5. Feature and target variable selection
6. Exploratory data analysis
7. Correlation matrix and heatmap
8. Manual calculation of regression coefficients using normal equations
9. Single-feature Linear Regression
10. Multiple Linear Regression
11. Standardised coefficient analysis
12. Actual vs predicted price comparison
13. Model evaluation using MAE, MSE, RMSE, R-squared and Adjusted R-squared
14. Residual analysis
15. Multicollinearity checking using VIF
16. Training and testing performance comparison
17. Prediction for a new house

## Model Performance

The multiple-feature model achieved the following test results:

| Metric | Result |
|---|---:|
| MAE | 1,141,982.03 |
| RMSE | 1,515,116.78 |
| R-squared | 0.5336 |
| Adjusted R-squared | 0.5110 |

The multiple-feature model performed better than the single-feature model.

- Single-feature Test R-squared: 0.2605
- Multiple-feature Test R-squared: 0.5336

## Multicollinearity Analysis
Variance Inflation Factor (VIF) was used to check multicollinearity among the selected features. All five features had VIF values between approximately 1.13 and 1.32, indicating no serious multicollinearity.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## Repository Contents
- `housing_price_prediction.ipynb` – Complete notebook containing the implementation, visualisations and model evaluation.
- `Housing.csv` – Dataset used for the project.

## Conclusion
The project demonstrates how Multiple Linear Regression can be used to estimate house prices based on multiple housing features. The multiple-feature model achieved better performance than the single-feature model, although its predictions are estimates and not guaranteed market prices.

## GitHub
[complexiota](https://github.com/complexiota)
