# Accuracy, Precision, Recall and F1 Score

## Introduction

Accuracy, Precision, Recall, and F1 Score are among the most important metrics used to evaluate classification models.

These metrics are derived from the Confusion Matrix and help assess model performance from different perspectives.

---

## Accuracy

### Definition

Accuracy measures the proportion of correctly classified observations.

### Formula

```text id="db11x4"
Accuracy = (TP + TN) / (TP + TN + FP + FN)
```

### Example

If a model correctly predicts 950 out of 1000 observations:

```text id="htdc2v"
Accuracy = 95%
```

---

## Advantages of Accuracy

* Easy to understand
* Useful for balanced datasets

---

## Limitations of Accuracy

Accuracy can be misleading when datasets are imbalanced.

Example:

```text id="a5q4h8"
Fraud Cases = 1%
Legitimate Cases = 99%
```

Predicting every transaction as legitimate gives:

```text id="rbrqha"
99% Accuracy
```

but the model is useless.

---

## Precision

### Definition

Precision measures how many predicted positive observations are actually positive.

### Formula

```text id="zld6sv"
Precision = TP / (TP + FP)
```

### Importance

High Precision means fewer false alarms.

---

## Example

In fraud detection:

```text id="vf07gs"
Predicted Frauds = 100
Actual Frauds = 90
```

Precision:

```text id="rxjlwm"
90%
```

---

## Recall

### Definition

Recall measures how many actual positive observations were correctly identified.

### Formula

```text id="r8xxiq"
Recall = TP / (TP + FN)
```

### Importance

High Recall means fewer missed positive cases.

---

## Example

In medical diagnosis:

```text id="xizs59"
Actual Patients = 100
Detected Patients = 95
```

Recall:

```text id="e13k0v"
95%
```

---

## F1 Score

### Definition

F1 Score combines Precision and Recall into a single metric.

It is useful when both false positives and false negatives are important.

### Formula

```text id="1psknq"
F1 Score = 2 × (Precision × Recall) / (Precision + Recall)
```

---

## Why Use F1 Score?

F1 Score provides a balanced evaluation.

Useful for:

* Fraud Detection
* Medical Diagnosis
* Spam Detection
* Customer Churn Prediction

---

## Comparison

| Metric    | Focus                        |
| --------- | ---------------------------- |
| Accuracy  | Overall correctness          |
| Precision | Minimize False Positives     |
| Recall    | Minimize False Negatives     |
| F1 Score  | Balance Precision and Recall |

---

## When to Use Which Metric?

### Use Accuracy

When classes are balanced.

Example:

* Student Pass/Fail Prediction

---

### Use Precision

When false positives are costly.

Example:

* Spam Detection

---

### Use Recall

When false negatives are costly.

Example:

* Disease Diagnosis

---

### Use F1 Score

When both error types are important.

Example:

* Fraud Detection

---

## Summary

Accuracy, Precision, Recall, and F1 Score are essential metrics for evaluating classification models. While Accuracy measures overall correctness, Precision focuses on false positives, Recall focuses on false negatives, and F1 Score balances both. Choosing the right metric depends on the business problem and dataset characteristics.

