Automated Cell Type Classification
Cell Type Annotation using KNN and K-Means Clustering
Project Overview
This project implements machine learning algorithms for automated cell type annotation based on protein abundance data. The system uses both supervised (K-Nearest Neighbors) and unsupervised (K-Means clustering) approaches to classify cells as normal or cancerous types.

Key Features
Data Preprocessing:

Quantile normalization
Z-score standardization
Principal Component Analysis (PCA) for visualization
Supervised Learning:

K-Nearest Neighbors (KNN) classifier with:
Manhattan and Euclidean distance metrics
Tie-breaking using inverse distance weighting
Majority voting for classification
Unsupervised Learning:

Bisecting K-Means clustering algorithm
Cluster splitting based on:
Maximum frequency (cluster size)
Maximum inertia (within-cluster variance)
Technical Implementation
Pure Python implementation using NumPy for vectorized operations
Modular design with separate functions for each algorithm component
Visualization of high-dimensional data using PCA
Applications
This system can be used for:

Automated cell type classification in biomedical research
Cancer cell identification from protein expression data
Exploratory data analysis of single-cell protein measurements
Usage
The project is implemented as a Python script with clearly marked sections:

Data loading and preprocessing
KNN classifier implementation
K-Means clustering implementation
Visualization functions
Example usage is shown in the if __name__ == "__main__": blocks throughout the code.

Requirements
Python 3.x
NumPy
pandas
scikit-learn
matplotlib
Future Work
Potential enhancements include:

Integration with deep learning approaches
Support for additional distance metrics
Improved visualization capabilities
Parallel processing for large datasets
This project was developed as part of an Artificial Intelligence course assignment, demonstrating practical applications of fundamental ML algorithms to real-world biological data analysis problems.
