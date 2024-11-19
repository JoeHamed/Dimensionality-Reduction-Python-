# Dimensionality Reduction and Classification
This project demonstrates the application of various dimensionality reduction techniques — `PCA`, `LDA`, and `Kernel PCA` — followed by Logistic Regression for classification.

## Features
Dimensionality reduction using:
Principal Component Analysis (PCA)
Linear Discriminant Analysis (LDA)
Kernel Principal Component Analysis (Kernel PCA)
Classification of wine categories using Logistic Regression.
Visualization of decision boundaries on both training and test sets.

## Dataset
The dataset used is Wine.csv, which contains:

Features: Chemical properties of wine.
Labels: Wine categories (target variable).
Dataset structure:

Independent variables: Columns 0 to -2.
Dependent variable: Last column.

## Techniques
1. Principal Component Analysis (PCA)
Reduces the dataset's dimensionality by finding components that maximize variance.

2. Linear Discriminant Analysis (LDA)
Reduces dimensionality while maximizing class separability.

3. Kernel Principal Component Analysis (Kernel PCA)
Applies the kernel trick to perform PCA in higher-dimensional space for non-linear separability.

Clone the repository:
git clone https://github.com/your-username/dimensionality-reduction.git

Usage
Run the script to perform dimensionality reduction and classification:
python dimensionality_reduction.py

The script will:

Apply PCA, LDA, and Kernel PCA to the dataset.
Train a Logistic Regression model.
Output confusion matrices, accuracy scores, and decision boundary visualizations for each technique.

Results
PCA
Accuracy: ~97%
Confusion Matrix:
[[13  1  0]
 [ 0 15  1]
 [ 0  0  7]]
LDA
Accuracy: ~100%
Confusion Matrix:
[[14  0  0]
 [ 0 16  0]
 [ 0  0  6]]
Kernel PCA
Accuracy: ~100%
Confusion Matrix:
[[14  0  0]
 [ 0 16  0]
 [ 0  0  6]]
