# Naive Bayes Classifier

This project contains a custom Python implementation of the **Naive Bayes classification algorithm**, focusing on probabilistic text classification and feature likelihood estimation built from scratch.

The implementation demonstrates the fundamental principles of Bayesian inference, including prior probability calculation, conditional probability estimation, and classification based on probabilistic decision rules.

## Features

- Implements the Naive Bayes classifier from scratch without using machine learning libraries.
- Calculates class prior probabilities from dataset distributions.
- Builds feature-frequency mappings for textual data analysis.
- Estimates conditional probabilities for extracted features.
- Supports probabilistic classification using likelihood calculations.
- Applies Gaussian distribution concepts for continuous feature probability estimation.

## Algorithm Overview

The implementation follows the core principles of the Naive Bayes algorithm:

1. Calculates prior probabilities for each class:

   **P(Class)**

   based on the frequency of class occurrences in the training dataset.

2. Extracts text features and creates vocabulary mappings using token frequency analysis.

3. Computes conditional probabilities:

   **P(Feature | Class)**

   to measure how likely each feature is associated with a specific class.

4. Combines prior and conditional probabilities using Bayes' theorem to determine the most probable class.

5. Uses Gaussian probability distribution calculations for continuous feature likelihood estimation.

## Technologies

- **Python 3**
- **Collections (Counter)** – Frequency counting, vocabulary construction, and statistical analysis.
- **NumPy** – Mathematical operations, vectorized calculations, and logarithmic probability computations.

## Mathematical Background

The Naive Bayes classifier is based on Bayes' theorem:

**P(Class | Features) ∝ P(Class) × P(Features | Class)**

The algorithm assumes conditional independence between features, allowing complex classification problems to be solved efficiently using probability estimation.

For Gaussian Naive Bayes, feature likelihoods are estimated using the mean and variance of each feature distribution.

## Output

The program provides:

- Calculated class probabilities
- Feature likelihood estimations
- Probability scores for each class
- Final classification prediction

## Applications

Naive Bayes classifiers are widely used in:

- Spam detection
- Sentiment analysis
- Document classification
- Text categorization
- Medical diagnosis systems
