# Principal Component Analysis (PCA)

## Introduction

Principal Component Analysis (PCA) is a dimensionality reduction technique used to simplify datasets while retaining as much information as possible.

It transforms a large set of variables into a smaller set of uncorrelated variables called Principal Components.

---

## Why PCA?

Real-world datasets often contain hundreds or thousands of features.

Problems caused by high-dimensional data:

* Increased computational cost
* Overfitting
* Difficulty in visualization
* Redundant information

PCA helps reduce complexity while preserving important patterns.

---

## What are Principal Components?

Principal Components are new variables created from the original features.

Characteristics:

* Uncorrelated
* Capture maximum variance
* Ranked by importance

---

## How PCA Works

### Step 1

Standardize the data.

### Step 2

Calculate covariance matrix.

### Step 3

Compute eigenvalues and eigenvectors.

### Step 4

Select principal components.

### Step 5

Transform data into lower dimensions.

---

## Workflow

```text
Raw Data
    ↓
Standardization
    ↓
Covariance Matrix
    ↓
Eigenvectors & Eigenvalues
    ↓
Select Components
    ↓
Reduced Dataset
```

---

## Advantages

* Reduces dimensionality
* Improves model efficiency
* Reduces overfitting
* Helps visualization

---

## Limitations

* Reduced interpretability
* Information loss possible
* Sensitive to scaling

---

## Applications

### Machine Learning

* Feature Reduction

### Image Processing

* Image Compression

### Finance

* Portfolio Analysis

### Data Visualization

* High-Dimensional Data Visualization

---

## Summary

PCA is a dimensionality reduction technique that transforms high-dimensional data into a smaller set of meaningful features while retaining maximum variance. It is widely used for feature reduction and visualization.

