# K-Means Clustering 

This folder contains a custom Python implementation of the K-Means Clustering algorithm, representing a foundational Unsupervised Learning method developed from scratch using coordinate geometry and centroid tracking.

##  Implemented Methodology
* **Centroid Initialization:** Assigning baseline starting vectors ($C_1, C_2$) within the multi-dimensional feature space.
* **Euclidean Distance Evaluation:** Computing spatial distance profiles from each data point ($A, B, C, D, E, F$) to all current cluster centroids.
* **Iterative Partitioning & Refinement:** Dynamically grouping data points into the closest cluster domain and shifting the centroids by calculating the mean coordinates of the updated cluster members until convergence.

##  Technologies Used
* **Python 3**
* **NumPy:** For high-performance vector math and distance metric loops.
* **Pandas:** For structural logging of coordinate maps, distance columns, and cluster group assignments.
