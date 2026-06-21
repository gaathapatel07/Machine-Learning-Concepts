# Bias and Variance

## Introduction

Bias and Variance are two fundamental sources of error in machine learning models.

Understanding the balance between bias and variance is crucial for building models that generalize well to unseen data.

This concept is known as the **Bias-Variance Tradeoff**.

---

## What is Bias?

Bias refers to the error caused by overly simplistic assumptions in the learning algorithm.

High bias models fail to capture underlying patterns in the data.

This results in:

* Underfitting
* Poor training performance
* Poor testing performance

### Characteristics of High Bias

* Oversimplified model
* Misses important relationships
* High prediction error

Example:

Using Linear Regression for highly non-linear data.

---

## What is Variance?

Variance refers to the model's sensitivity to changes in training data.

High variance models learn the training data too closely, including noise.

This results in:

* Overfitting
* Excellent training accuracy
* Poor testing accuracy

### Characteristics of High Variance

* Complex model
* Learns noise and outliers
* Poor generalization

Example:

Deep Decision Trees without pruning.

---

## Underfitting vs Overfitting

### Underfitting

```text
High Bias
Low Variance
```

Characteristics:

* Poor training performance
* Poor testing performance

---

### Overfitting

```text
Low Bias
High Variance
```

Characteristics:

* Excellent training performance
* Poor testing performance

---

### Ideal Model

```text
Moderate Bias
Moderate Variance
```

Characteristics:

* Good training accuracy
* Good testing accuracy
* Strong generalization

---

## Bias-Variance Tradeoff

As model complexity increases:

* Bias decreases
* Variance increases

As model complexity decreases:

* Bias increases
* Variance decreases

The goal is to find the optimal balance.

---

## Methods to Reduce Bias

* Increase model complexity
* Add relevant features
* Use advanced algorithms
* Reduce regularization

---

## Methods to Reduce Variance

* Collect more data
* Simplify the model
* Use regularization
* Apply cross-validation
* Remove noisy features

---

## Real-World Example

### House Price Prediction

High Bias:

* Predicts all houses using a simple average.

High Variance:

* Memorizes every training example.

Balanced Model:

* Learns meaningful relationships while generalizing to new houses.

---

## Summary

Bias represents errors due to overly simple assumptions, while variance represents errors due to excessive sensitivity to training data. Successful machine learning models maintain a balance between bias and variance to achieve strong generalization performance.

