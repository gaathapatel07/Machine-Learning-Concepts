
# Linear Regression

## Introduction

Linear Regression is one of the most fundamental supervised machine learning algorithms used for predicting continuous numerical values.

It establishes a linear relationship between independent variables (features) and a dependent variable (target).

Examples include:

* House Price Prediction
* Sales Forecasting
* Stock Trend Analysis
* Revenue Prediction

---

## What is Linear Regression?

Linear Regression attempts to find the best-fit straight line that describes the relationship between input variables and output values.

The line is known as the **Regression Line**.

---

## Mathematical Equation

Where:

* y = Dependent Variable
* x = Independent Variable
* m = Slope
* b = Intercept

---

## How Linear Regression Works

```text
Input Data
      ↓
Find Best Fit Line
      ↓
Learn Relationship
      ↓
Predict Future Values
```

The algorithm minimizes the difference between actual values and predicted values.

---

## Types of Linear Regression

### Simple Linear Regression

Uses one independent variable.

Example:

```text
House Price = f(House Area)
```

---

### Multiple Linear Regression

Uses multiple independent variables.

Example:

```text
House Price = f(Area, Bedrooms, Location)
```

---

## Assumptions of Linear Regression

1. Linear Relationship
2. Independence of Observations
3. Homoscedasticity
4. Normal Distribution of Errors
5. No Multicollinearity

---

## Advantages

* Simple and interpretable
* Fast to train
* Easy to implement
* Works well for linear relationships

---

## Limitations

* Assumes linearity
* Sensitive to outliers
* Cannot model complex patterns
* Performance decreases with non-linear data

---

## Evaluation Metrics

### Mean Absolute Error (MAE)

Average absolute difference between actual and predicted values.

### Mean Squared Error (MSE)

Average squared prediction error.

### Root Mean Squared Error (RMSE)

Square root of MSE.

### R-Squared Score

Measures how much variance is explained by the model.

Range:

```text
0 to 1
```

Higher values indicate better performance.

---

## Applications

### Finance

* Revenue Forecasting
* Stock Trend Analysis

### Real Estate

* House Price Prediction

### Marketing

* Sales Prediction
* Customer Spending Analysis

### Business Analytics

* Demand Forecasting
* Growth Prediction

---

## Real-World Example

Suppose a company wants to predict monthly sales based on advertising expenditure.

Input:

```text
Advertising Budget
```

Output:

```text
Monthly Sales
```

Linear Regression identifies the relationship between advertising spend and sales, allowing future sales predictions.

---

## Summary

Linear Regression is a supervised learning algorithm used for predicting continuous values by modeling a linear relationship between input features and the target variable. Due to its simplicity, interpretability, and efficiency, it remains one of the most widely used algorithms in data analytics and machine learning.
