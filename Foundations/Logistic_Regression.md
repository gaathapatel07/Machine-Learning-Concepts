# Logistic Regression

## Introduction

Logistic Regression is a supervised machine learning algorithm used for classification problems. Unlike Linear Regression, which predicts continuous values, Logistic Regression predicts the probability that an observation belongs to a particular class.

It is one of the most widely used algorithms for binary classification tasks.

Examples include:

* Fraud Detection
* Spam Email Detection
* Customer Churn Prediction
* Disease Diagnosis
* Loan Default Prediction

---

## What is Logistic Regression?

Logistic Regression estimates the probability that a given input belongs to a specific category.

The output is always between:

```text
0 and 1
```

The probability is then converted into class labels.

Example:

```text
Probability = 0.92 → Fraud
Probability = 0.15 → Not Fraud
```

---

## Why Not Use Linear Regression for Classification?

Linear Regression can produce values outside the range:

```text
0 to 1
```

which cannot be interpreted as probabilities.

Logistic Regression solves this problem using the Sigmoid Function.

---

## Sigmoid Function

The Sigmoid Function transforms any real number into a value between 0 and 1.

### Properties

* Output ranges from 0 to 1
* Produces probability estimates
* Smooth and differentiable
* Suitable for binary classification

---

## How Logistic Regression Works

```text
Input Features
       ↓
Linear Combination
       ↓
Sigmoid Function
       ↓
Probability
       ↓
Class Prediction
```

---

## Classification Threshold

A threshold is used to convert probabilities into classes.

Common threshold:

```text
0.5
```

Example:

| Probability | Prediction |
| ----------- | ---------- |
| 0.85        | Positive   |
| 0.72        | Positive   |
| 0.35        | Negative   |
| 0.12        | Negative   |

---

## Types of Logistic Regression

### Binary Logistic Regression

Two possible outcomes.

Examples:

* Fraud / Not Fraud
* Yes / No
* Pass / Fail

---

### Multinomial Logistic Regression

More than two categories.

Examples:

* Predicting Product Category
* Predicting Customer Segment

---

### Ordinal Logistic Regression

Categories have a meaningful order.

Examples:

* Low, Medium, High
* Poor, Average, Excellent

---

## Advantages

* Simple and interpretable
* Fast training process
* Provides probability scores
* Effective for linearly separable data
* Works well on small and medium datasets

---

## Limitations

* Assumes linear decision boundaries
* Sensitive to outliers
* Struggles with complex relationships
* Performance decreases with highly nonlinear data

---

## Evaluation Metrics

### Accuracy

Percentage of correctly classified observations.

### Precision

Measures the proportion of predicted positives that are actually positive.

### Recall

Measures the proportion of actual positives correctly identified.

### F1 Score

Balances Precision and Recall.

### ROC-AUC

Measures the model's ability to distinguish between classes.

---

## Applications

### Finance

* Fraud Detection
* Credit Risk Assessment

### Healthcare

* Disease Diagnosis
* Patient Risk Prediction

### Marketing

* Customer Churn Prediction
* Lead Conversion Prediction

### Cybersecurity

* Intrusion Detection
* Spam Detection

---

## Real-World Example

A bank wants to identify fraudulent transactions.

Input Features:

* Transaction Amount
* Merchant Category
* Transaction Time
* Location

Output:

```text
Fraud
Not Fraud
```

Logistic Regression predicts the probability that a transaction is fraudulent and classifies it accordingly.

---

## Logistic Regression vs Linear Regression

| Feature      | Linear Regression | Logistic Regression |
| ------------ | ----------------- | ------------------- |
| Problem Type | Regression        | Classification      |
| Output       | Continuous Values | Probability         |
| Range        | Any Value         | 0 to 1              |
| Use Cases    | Price Prediction  | Fraud Detection     |

---

## Summary

Logistic Regression is a supervised learning algorithm primarily used for classification tasks. By transforming predictions into probabilities using the Sigmoid Function, it enables accurate decision-making for binary and multiclass classification problems. Due to its simplicity, interpretability, and effectiveness, Logistic Regression remains one of the most important algorithms in machine learning.

