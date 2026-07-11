# Linear Regression Solver

This folder contains a custom Python implementation of the Multiple Linear Regression algorithm, built using analytical matrix mathematics and deterministic solvers without leveraging high-level ML frameworks.

##  Implemented Methodology
* **Matrix Formulation ($A \cdot W = B$):** Constructing feature cross-product matrices and target vectors to set up the system of normal equations for OLS (Ordinary Least Squares) estimation.
* **Analytical Parameter Estimation:** Computing the optimal weight vector ($W$) through matrix transformations to minimize the global residual sum of squares.
* **Train-Test Evaluation Split:** Partitioning the structured numerical dataset into explicit training domains and testing matrix subsets to validate inference precision and model generalization.

##  Technologies Used
* **Python 3**
* **NumPy:** For high-performance matrix multiplications (`@` operator), system solvers, and transpose mechanics.
* **Pandas:** For structured data framing, row indexing, and analytical validation tracking.
