# Support Vector Machine (SVM)

## Introduction

Support Vector Machine (SVM) is a supervised machine learning algorithm used for both classification and regression tasks. It is particularly effective for classification problems involving high-dimensional datasets.

The main objective of SVM is to find the optimal boundary that best separates different classes.

---

## What is a Hyperplane?

A Hyperplane is a decision boundary that separates data points into different classes.

Example:

```text id="j2xq6r"
Fraud Transactions
        |
        |
Hyperplane
        |
        |
Legitimate Transactions
```

The goal is to maximize the distance between the hyperplane and the nearest data points.

---

## Support Vectors

Support Vectors are the data points closest to the decision boundary.

These points play a crucial role in determining the position of the hyperplane.

Without support vectors, the hyperplane would change significantly.

---

## How SVM Works

```text id="n8t0az"
Input Data
      ↓
Find Optimal Hyperplane
      ↓
Maximize Margin
      ↓
Classify New Data
```

---

## Types of SVM

### Linear SVM

Used when data can be separated using a straight line.

Applications:

* Spam Detection
* Fraud Detection

---

### Non-Linear SVM

Used when data cannot be separated linearly.

Uses Kernel Functions to transform data into higher dimensions.

---

## Kernel Functions

### Linear Kernel

Used for linearly separable data.

### Polynomial Kernel

Captures polynomial relationships.

### Radial Basis Function (RBF)

Most commonly used kernel.

Handles complex nonlinear patterns.

### Sigmoid Kernel

Similar to neural network activation functions.

---

## Advantages

* Effective in high-dimensional spaces
* Works well with small datasets
* Robust against overfitting
* Handles complex decision boundaries

---

## Limitations

* Computationally expensive
* Difficult to interpret
* Sensitive to parameter tuning
* Slower on large datasets

---

## Applications

### Finance

* Fraud Detection
* Credit Risk Analysis

### Healthcare

* Disease Classification
* Medical Diagnosis

### Cybersecurity

* Malware Detection
* Intrusion Detection

### Image Processing

* Face Recognition
* Object Classification

---

## Summary

Support Vector Machine is a powerful supervised learning algorithm that finds the optimal boundary between classes. Due to its ability to handle high-dimensional and nonlinear data, SVM remains a popular choice for classification problems.

