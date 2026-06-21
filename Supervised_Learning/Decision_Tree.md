# Decision Tree

## Introduction

Decision Tree is a supervised machine learning algorithm used for both classification and regression tasks. It mimics human decision-making by splitting data into smaller subsets based on feature values.

The structure resembles a tree where each internal node represents a decision, branches represent possible outcomes, and leaf nodes represent final predictions.

---

## How Decision Trees Work

A Decision Tree repeatedly splits data into smaller groups based on the most informative feature.

Example:

```text
Transaction Amount > ₹10,000?
         /      \
       Yes      No
        |        |
  International? Legitimate
      /   \
    Yes   No
     |     |
   Fraud Legitimate
```

---

## Components of a Decision Tree

### Root Node

The top-most node representing the entire dataset.

### Decision Node

A node where the dataset is split based on a condition.

### Leaf Node

The final prediction or outcome.

### Branch

A connection between nodes.

---

## Splitting Criteria

### Gini Impurity

Measures how often a randomly chosen element would be incorrectly classified.

Lower Gini Impurity indicates better splits.

### Entropy

Measures disorder or uncertainty in data.

Lower entropy indicates purer groups.

---

## Advantages

* Easy to understand and visualize
* Handles numerical and categorical data
* Requires minimal preprocessing
* Useful for feature importance analysis

---

## Limitations

* Prone to overfitting
* Sensitive to small changes in data
* Can create overly complex trees

---

## Applications

* Fraud Detection
* Customer Churn Prediction
* Medical Diagnosis
* Loan Approval Systems
* Risk Assessment

---

## Summary

Decision Trees are intuitive machine learning models that make predictions through a sequence of decisions. They are easy to interpret but require careful tuning to avoid overfitting.

