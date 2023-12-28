# K-Nearest Neighbors (KNN)

## Introduction

K-Nearest Neighbors (KNN) is a simple, lazy learning algorithm used for classification and regression. In both cases, the input consists of the *k* closest training examples in the feature space.

---

## How It Works

### Step 1: Select K
Choose the number of neighbors, `k`.

### Step 2: Compute Distance
Calculate the distance (usually Euclidean) from a given new point to all other points in the dataset.

### Step 3: Sort and Select
Sort these distances and select the top `k` points.

### Step 4: Majority Voting
For classification, a majority vote is done among the `k` neighbors to decide the class of the new point. For regression, the average output value of the `k` neighbors is used.

---

## Use Cases

- Text recognition
- Stock market forecasting
- Medical diagnosis

---

## Pros and Cons

### Pros

1. Simple to implement
2. Works well with small datasets

### Cons

1. Not suitable for large datasets
2. Sensitive to irrelevant features

---

## Conclusion

KNN is a straightforward yet powerful algorithm. However, it's often not the first choice for large-scale applications but can work very well for smaller datasets or as a part of a more complex ensemble method.
