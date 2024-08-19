# Salary Prediction using Linear and Polynomial Regression

This project demonstrates the use of both Linear and Polynomial Regression models to predict salaries based on the position level of employees. By using a dataset that contains position levels and their corresponding salaries, this project showcases the differences between linear and polynomial models in fitting data and making predictions.

## Detailed Summary

The script starts by importing a dataset containing employee position levels and their salaries. It implements both **Linear Regression** and **Polynomial Regression** models to predict salaries based on position level. The project compares the performance of the two models by visualizing their results, highlighting how polynomial regression can provide a more flexible and accurate fit for non-linear data.

The script performs the following steps:

1. **Data Preprocessing:** Loads the dataset and splits it into independent variable (position level) and dependent variable (salary).
2. **Linear Regression Model:** Trains a linear regression model on the entire dataset and visualizes the results with a regression line.
3. **Polynomial Regression Model:** Transforms the input features into polynomial features and trains a polynomial regression model (degree 4) on the entire dataset.
4. **Visualization:** The script visualizes the results for both models, showing the difference in how linear and polynomial regression fits the data. Additionally, a higher resolution plot is created for polynomial regression to smooth the curve.
5. **Prediction:** The script makes predictions for a position level of 6.5 using both the linear and polynomial regression models and outputs the predicted salaries.

