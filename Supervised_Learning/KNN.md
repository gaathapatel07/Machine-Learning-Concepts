# K-Nearest Neighbors (KNN)

## Introduction

K-Nearest Neighbors (KNN) is a supervised machine learning algorithm used for classification and regression tasks.

KNN predicts the class of a new data point by examining the classes of its nearest neighbors.

It is known as a lazy learning algorithm because it stores training data and makes predictions only when required.

---

## How KNN Works

### Step 1

Choose the value of K.

Example:

```text
K = 5
```

### Step 2

Calculate the distance between the new data point and all existing points.

### Step 3

Select the K nearest neighbors.

### Step 4

Use majority voting to determine the prediction.

---

## Example

Suppose a new customer needs classification.

Nearest neighbors:

```text
Customer 1 → Premium
Customer 2 → Premium
Customer 3 → Premium
Customer 4 → Basic
Customer 5 → Basic
```

Prediction:

```text
Premium
```

---

## Distance Metrics

### Euclidean Distance

Most commonly used distance metric.

Measures straight-line distance between two points.

### Manhattan Distance

Measures distance along grid-like paths.

---

## Choosing K

Small K:

* Sensitive to noise
* Higher variance

Large K:

* More stable
* Higher bias

---

## Advantages

* Easy to understand
* No training phase
* Effective for small datasets

---

## Limitations

* Slow for large datasets
* Sensitive to feature scaling
* Performance decreases with high-dimensional data

---

## Applications

* Recommendation Systems
* Image Classification
* Pattern Recognition
* Customer Segmentation

---

## Summary

KNN is a simple yet powerful machine learning algorithm that classifies data based on similarity. It is particularly useful for small datasets and introductory machine learning applications.

