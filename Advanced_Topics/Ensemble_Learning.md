# Ensemble Learning

## Introduction

Ensemble Learning is a machine learning technique that combines multiple models to produce a stronger and more accurate predictive model.

Instead of relying on a single algorithm, ensemble methods aggregate predictions from several models to improve performance, reduce errors, and increase robustness.

The basic idea is:

> A group of weak learners can collectively become a strong learner.

---

## Why Ensemble Learning?

Single models often suffer from:

* High bias
* High variance
* Overfitting
* Poor generalization

Ensemble methods help overcome these limitations.

Benefits:

* Higher accuracy
* Better stability
* Reduced overfitting
* Improved generalization

---

## Types of Ensemble Learning

### Bagging (Bootstrap Aggregating)

Multiple models are trained independently on random subsets of data.

Final prediction is obtained through:

* Majority voting (Classification)
* Averaging (Regression)

Example:

* Random Forest

---

### Boosting

Models are trained sequentially.

Each new model focuses on correcting errors made by previous models.

Examples:

* AdaBoost
* Gradient Boosting
* XGBoost

---

### Stacking

Multiple models are combined and a meta-model learns how to combine their predictions.

Example:

```text id="o5przs"
Model 1 → Prediction
Model 2 → Prediction
Model 3 → Prediction
        ↓
 Meta Model
        ↓
 Final Prediction
```

---

## Advantages

* Improved prediction accuracy
* Better handling of complex datasets
* Reduced variance and bias
* Stronger generalization capability

---

## Limitations

* Increased computational cost
* Longer training times
* Reduced interpretability

---

## Applications

* Fraud Detection
* Credit Scoring
* Recommendation Systems
* Customer Churn Prediction
* Medical Diagnosis

---

## Summary

Ensemble Learning combines multiple machine learning models to create a more accurate and reliable predictor. Popular ensemble methods include Bagging, Boosting, and Stacking, all of which are widely used in real-world machine learning applications.

