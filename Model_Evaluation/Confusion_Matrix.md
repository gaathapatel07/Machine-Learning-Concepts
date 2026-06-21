
# Confusion Matrix

## Introduction

A Confusion Matrix is a performance evaluation tool used to measure the effectiveness of classification models.

It provides a detailed breakdown of prediction results and helps understand where a model is making mistakes.

Unlike accuracy alone, a confusion matrix reveals the types of errors being made.

---

## Structure of a Confusion Matrix

| Actual / Predicted | Positive            | Negative            |
| ------------------ | ------------------- | ------------------- |
| Positive           | True Positive (TP)  | False Negative (FN) |
| Negative           | False Positive (FP) | True Negative (TN)  |

---

## Components

### True Positive (TP)

The model correctly predicts a positive class.

Example:

```text id="j2gw3v"
Actual Fraud = Fraud
Predicted Fraud = Fraud
```

---

### True Negative (TN)

The model correctly predicts a negative class.

Example:

```text id="jw90r8"
Actual Legitimate = Legitimate
Predicted Legitimate = Legitimate
```

---

### False Positive (FP)

The model incorrectly predicts a positive class.

Example:

```text id="hr4rrf"
Actual Legitimate = Legitimate
Predicted Legitimate = Fraud
```

Also called:

```text id="7axm18"
Type I Error
```

---

### False Negative (FN)

The model incorrectly predicts a negative class.

Example:

```text id="0n5n3y"
Actual Fraud = Fraud
Predicted Fraud = Legitimate
```

Also called:

```text id="s7y8j9"
Type II Error
```

---

## Why Confusion Matrix is Important

Benefits:

* Identifies prediction errors
* Helps calculate evaluation metrics
* Useful for imbalanced datasets
* Provides deeper model insights

---

## Example

Suppose a fraud detection model produces:

| Actual / Predicted | Fraud | Legitimate |
| ------------------ | ----- | ---------- |
| Fraud              | 80    | 20         |
| Legitimate         | 10    | 890        |

Interpretation:

* TP = 80
* FN = 20
* FP = 10
* TN = 890

---

## Applications

* Fraud Detection
* Disease Diagnosis
* Spam Detection
* Customer Churn Prediction

---

## Summary

A Confusion Matrix provides a detailed evaluation of classification models by showing correct and incorrect predictions. It forms the foundation for metrics such as Accuracy, Precision, Recall, and F1 Score.
