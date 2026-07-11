# Hopfield Autoassociative Network 

This directory features a custom Python implementation of a discrete Hopfield Neural Network, demonstrating the mechanics of recurrent associative memory and state convergence using pure matrix calculus.

##  Implemented Methodology
* **Hebbian Matrix Learning:** Constructing a symmetric weight correlation matrix ($W$) by computing the outer products of bipolar prototype vectors ($\vec{p} \in \{-1, 1\}^n$) and enforcing a zero-diagonal constraint ($w_{ii} = 0$) to eliminate self-feedback loops.
* **Energy Minimization & Convergence:** Simulating state transitions by applying a sign activation function over dot product fields to iteratively steer corrupted inputs into stable local minima (attractors).
* **Associative Recall Execution:** Verifying complete memory pattern restoration from partial or noisy initial states across recursive training tracks.

##  Technologies Used
* **Python 3**
* **NumPy:** For vector outer products, matrix transformations, and array updates.
