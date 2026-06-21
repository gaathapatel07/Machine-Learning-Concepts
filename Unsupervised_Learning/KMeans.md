# K-Means Clustering

## Introduction

K-Means is one of the most popular unsupervised machine learning algorithms used for clustering.

The goal of K-Means is to group similar data points into clusters such that points within the same cluster are more similar to each other than points in different clusters.

Unlike supervised learning, K-Means works with unlabeled data.

---

## What is Clustering?

Clustering is the process of dividing data into groups based on similarity.

Examples:

* Customer Segmentation
* Market Basket Analysis
* Image Compression
* Recommendation Systems

---

## How K-Means Works

### Step 1

Choose the number of clusters (K).

Example:

```text
K = 3
```

---

### Step 2

Randomly initialize K centroids.

A centroid represents the center of a cluster.

---

### Step 3

Assign each data point to the nearest centroid.

---

### Step 4

Recalculate cluster centroids.

---

### Step 5

Repeat until centroids stop changing.

---

## Workflow

```text
Choose K
    ↓
Initialize Centroids
    ↓
Assign Points to Clusters
    ↓
Update Centroids
    ↓
Repeat Until Convergence
```

---

## Choosing the Optimal K

### Elbow Method

The Elbow Method helps determine the optimal number of clusters.

The ideal K is selected where adding more clusters results in diminishing improvement.

---

## Advantages

* Simple and easy to implement
* Fast on large datasets
* Scalable
* Works well with well-separated clusters

---

## Limitations

* Requires choosing K beforehand
* Sensitive to outliers
* Struggles with irregular cluster shapes

---

## Applications

### Marketing

* Customer Segmentation

### Finance

* Risk Profiling

### E-Commerce

* Product Recommendation Systems

### Healthcare

* Patient Grouping

---

## Summary

K-Means is an unsupervised learning algorithm used to group similar observations into clusters. Due to its simplicity and effectiveness, it remains one of the most widely used clustering techniques in data science.

