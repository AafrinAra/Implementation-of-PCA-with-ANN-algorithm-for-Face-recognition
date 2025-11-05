# Implementation-of-PCA-with-ANN-algorithm-for-Face-recognition

Implementation of PCA with ANN Algorithm for Face Recognition


This project implements a Face Recognition System using Principal Component Analysis (PCA) for feature extraction (Eigenfaces) and a Multi-Layer Perceptron (ANN) for classification. The goal is to recognize human faces from images efficiently by reducing dimensionality and training a neural network on the key facial features.


Image Preprocessing:
  Load all face images from the dataset
  Convert to grayscale and resize for uniformity
Feature Extraction using PCA:
  Reduce high-dimensional image data into principal components
  Generate Eigenfaces representing the most significant facial features
Dimensionality Reduction using LDA (optional):
  Enhance class separability before classification
Face Classification using ANN (MLP):
  Train a neural network to classify faces based on extracted features
  Evaluate model accuracy on test data
Visualization:
  Display Eigenfaces and predicted face results with confidence scores

 Technologies Used
   Python
   OpenCV
   NumPy & Matplotlib
   Scikit-learn (PCA, LDA, MLPClassifier)
   Joblib (for saving trained models)
