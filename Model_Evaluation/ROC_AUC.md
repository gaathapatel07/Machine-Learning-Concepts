# ROC Curve and AUC

## Introduction

ROC (Receiver Operating Characteristic) Curve and AUC (Area Under the Curve) are important evaluation metrics used for classification models.

They measure a model's ability to distinguish between positive and negative classes.

ROC-AUC is particularly useful when working with imbalanced datasets such as fraud detection.

---

## What is ROC Curve?

The ROC Curve is a graphical representation of model performance at different classification thresholds.

It plots:

```text
True Positive Rate (TPR)
vs
False Positive Rate (FPR)
```

---

## True Positive Rate

Also known as Recall.

Formula:

```text
TPR = TP / (TP + FN)
```

Measures how many actual positives are correctly identified.

---

## False Positive Rate

Formula:

```text
FPR = FP / (FP + TN)
```

Measures how many actual negatives are incorrectly classified as positive.

---

## ROC Curve Interpretation

A good model:

* High True Positive Rate
* Low False Positive Rate

The closer the curve is to the top-left corner, the better the model.

---

## What is AUC?

AUC stands for Area Under the ROC Curve.

It summarizes the overall performance of a classifier.

Range:

```text
0 to 1
```

---

## AUC Interpretation

| AUC Score   | Performance     |
| ----------- | --------------- |
| 0.50        | Random Guessing |
| 0.60 - 0.70 | Poor            |
| 0.70 - 0.80 | Fair            |
| 0.80 - 0.90 | Good            |
| 0.90 - 1.00 | Excellent       |

---

## Why ROC-AUC is Important

Advantages:

* Threshold independent
* Works well with imbalanced data
* Measures ranking ability
* Useful for comparing models

---

## Example

Fraud Detection:

Model A:

```text
AUC = 0.78
```

Model B:

```text
AUC = 0.92
```

Model B performs significantly better at distinguishing fraudulent and legitimate transactions.

---

## Applications

* Fraud Detection
* Medical Diagnosis
* Credit Risk Assessment
* Customer Churn Prediction

---

## Summary

ROC Curve and AUC are powerful evaluation tools used to measure classification performance. They provide insights into how effectively a model distinguishes between classes and are widely used in real-world machine learning applications.

