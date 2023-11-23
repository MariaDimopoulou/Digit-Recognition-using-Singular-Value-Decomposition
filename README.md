# Digit Recognition using Singular Value Decomposition (SVD)

## Overview
This project focuses on digit recognition using Singular Value Decomposition (SVD) as a dimensionality reduction technique. The dataset used for training and testing contains handwritten digits in a matrix format.

## Prerequisites
Make sure you have the following dependencies installed:

- Python (>=3.6)
- Required Python packages: `matplotlib`, `pandas`, `numpy`, `scipy`, `scikit-learn`

## Dataset
The dataset consists of two main parts:
- **Training Data:**
  - Features (`xtrain`): Handwritten digit images in matrix form.
  - Labels (`ytrain`): Corresponding digit labels for training.
- **Testing Data:**
  - Features (`xtest`): Handwritten digit images for testing.
  - Labels (`ytest`): True labels for testing data.

## Preprocessing
1. Displaying Digits: The `show_digit` function takes the index of a column and displays the corresponding digit from the dataset.
2. Creating Matrices: Matrices for each digit (0-9) are extracted from the training data.

## Dimensionality Reduction with SVD
1. SVD Analysis: Singular Value Decomposition is applied to each digit's matrix.
2. Optimal Number of Basis Vectors: The accuracy of the digit recognition model is evaluated for different numbers of basis vectors.

## Results
1. Accuracy Scores: The accuracy scores for various numbers of basis vectors are displayed.
2. Confusion Matrix: A confusion matrix is generated for the model with the optimal number of basis vectors.

## Observations
1. Common Misclassifications: Some commonly misclassified digits are displayed, providing insights into the model's performance.
2. Impact of Changes: The impact of changing the number of basis vectors for specific digits is explored.

