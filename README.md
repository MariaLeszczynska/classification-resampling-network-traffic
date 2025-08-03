# Network traffic classification with resampling and evaluation

This project focuses on detecting and classifying malicious and benign network traffic using supervised machine learning models. It was originally prepared for a university machine learning task involving a heavily imbalanced dataset.

## Objective – accurately classify network traffic into one of six categories (clear, donbot, fast_flux, neris, qvod, rbot), while handling missing data and severe class imbalance.

## Features:
- End-to-end ML pipeline including:
  - Cleaning, preprocessing, and transformation
  - Dimensionality reduction via PCA
  - Outlier detection (IQR based)
  - Class imbalance handled with SMOTE
- Models evaluated:
  - Logistic Regression
  - Random Forest
  - Support Vector Classifier (SVC)
  - K-Nearest Neighbors (KNN)
  - Gaussian Naive Bayes
- Stratified 5-fold validation and performance aggregation
- Visualizations for:
  - Class distribution before and after resampling
  - Missing value analysis
  - Feature correlations
