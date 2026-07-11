# K-Means Clustering from Scratch

This project contains a custom Python implementation of the **K-Means Clustering algorithm**, one of the most widely used **Unsupervised Learning** techniques.

The algorithm is implemented from scratch without using machine learning libraries, focusing on the mathematical principles behind clustering, including centroid initialization, distance calculation, cluster assignment, and iterative centroid optimization.

## Features

- Implements K-Means clustering without using external machine learning frameworks.
- Initializes cluster centroids manually in a multi-dimensional feature space.
- Calculates Euclidean distances between data points and cluster centers.
- Assigns points to the nearest cluster based on distance metrics.
- Updates centroids using the mean coordinates of cluster members.
- Repeats the optimization process until convergence.

## Algorithm Overview

The implementation follows the standard K-Means workflow:

1. **Centroid Initialization**

   Initial cluster centers are selected:

   **C₁, C₂**

   representing the starting positions of the clusters.

2. **Distance Calculation**

   The Euclidean distance between each data point and every centroid is calculated:

   **d(x, C) = √Σ(xᵢ - Cᵢ)²**

3. **Cluster Assignment**

   Each data point is assigned to the closest centroid based on the minimum calculated distance.

4. **Centroid Update**

   New centroid positions are calculated using the mean coordinates of all points belonging to each cluster.

5. **Iteration**

   Steps 2–4 are repeated until centroid positions stop changing and the algorithm reaches convergence.

## Technologies

- **Python 3**
- **NumPy** – Vectorized mathematical operations, distance calculations, and numerical processing.
- **Pandas** – Data organization, coordinate tracking, distance tables, and cluster assignment visualization.

## Mathematical Background

K-Means clustering aims to minimize the distance between data points and their corresponding cluster centroids.

The objective function is based on minimizing the within-cluster sum of squares:

**Σ ||x - C||²**

where:

- **x** represents a data point.
- **C** represents the centroid of the assigned cluster.

The algorithm iteratively improves cluster positions by reducing the total distance between points and their cluster centers.

## Output

The program provides:

- Distance calculations between points and centroids.
- Cluster assignment results.
- Updated centroid coordinates.
- Final cluster distribution after convergence.

## Applications

K-Means clustering is commonly used in:

- Customer segmentation
- Image compression
- Pattern recognition
- Market analysis
- Data exploration
- Anomaly detection
