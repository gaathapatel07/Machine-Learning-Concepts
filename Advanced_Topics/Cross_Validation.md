# Cross Validation

## Introduction

Cross Validation is a model evaluation technique used to assess how well a machine learning model generalizes to unseen data.

Instead of evaluating a model using a single train-test split, Cross Validation repeatedly trains and tests the model on different subsets of the dataset.

This provides a more reliable estimate of model performance.

---

## Why Cross Validation?

A single train-test split may produce misleading results because performance can depend on how the data is divided.

Cross Validation helps:

* Reduce evaluation bias
* Improve reliability
* Detect overfitting
* Improve model selection

---

## Train-Test Split vs Cross Validation

| Train-Test Split         | Cross Validation  |
| ------------------------ | ----------------- |
| Single Split             | Multiple Splits   |
| Faster                   | More Reliable     |
| Higher Variance          | Lower Variance    |
| Less Accurate Evaluation | Better Evaluation |

---

## K-Fold Cross Validation

The dataset is divided into K equal parts.

Example:

```text id="s4abzt"
K = 5
```

Workflow:

```text id="f4v6xj"
Fold 1 → Test
Fold 2-5 → Train

Fold 2 → Test
Fold 1,3,4,5 → Train

Continue until all folds are tested
```

The final performance is the average across all folds.

---

## Stratified K-Fold

Maintains class distribution in every fold.

Useful for:

* Fraud Detection
* Customer Churn Prediction
* Medical Diagnosis

---

## Leave-One-Out Cross Validation

Each observation becomes a test sample once.

Advantages:

* Maximum training data usage

Disadvantages:

* Computationally expensive

---

## Benefits

* Better model evaluation
* Reduced overfitting risk
* Improved generalization
* More stable results

---

## Applications

* Model Selection
* Hyperparameter Tuning
* Performance Comparison

---

## Summary

Cross Validation is a robust evaluation technique that improves model assessment by repeatedly training and testing on different subsets of data. It provides a more accurate estimate of real-world performance than a single train-test split.

