# Random Forest

## Introduction

Random Forest is an ensemble learning algorithm that combines multiple Decision Trees to improve prediction accuracy and reduce overfitting.

Instead of relying on a single tree, Random Forest aggregates predictions from many trees and selects the most common result.

---

## Why Random Forest?

A single Decision Tree may memorize training data and overfit.

Random Forest solves this problem by:

* Building multiple trees
* Training each tree on different samples
* Combining predictions

This leads to better generalization.

---

## How Random Forest Works

```text
Dataset
   ↓
Multiple Random Samples
   ↓
Decision Tree 1
Decision Tree 2
Decision Tree 3
...
Decision Tree N
   ↓
Combine Predictions
   ↓
Final Output
```

---

## Types of Predictions

### Classification

Uses majority voting.

Example:

```text
Tree 1 → Fraud
Tree 2 → Fraud
Tree 3 → Legitimate

Final Prediction → Fraud
```

### Regression

Uses average prediction from all trees.

---

## Advantages

* High accuracy
* Reduces overfitting
* Handles missing values effectively
* Works well on large datasets

---

## Limitations

* Computationally expensive
* Slower training time
* Less interpretable than a single Decision Tree

---

## Applications

* Fraud Detection
* Credit Risk Analysis
* Customer Segmentation
* Recommendation Systems
* Medical Diagnosis

---

## Summary

Random Forest combines multiple Decision Trees to create a robust and accurate predictive model. It is one of the most widely used machine learning algorithms due to its reliability and strong performance.
