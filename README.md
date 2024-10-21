# Anomaly Detection Using Gaussian Mixture Models

## Overview
This project implements an anomaly detection system using Gaussian Mixture Models (GMM) to identify outliers in a dataset. The model estimates the mean and variance of the features in the training set and uses these parameters to evaluate the likelihood of instances in both the training and validation sets. The optimal threshold for classifying anomalies is determined using cross-validation.

## Features
- **Gaussian Parameter Estimation**: Calculates the mean and variance of features from the training dataset.
- **Probability Evaluation**: Computes the probability density for each instance based on the estimated Gaussian parameters.
- **Threshold Selection**: Utilizes a validation set to determine the best threshold for classifying anomalies, optimizing for the F1 score.
- **Anomaly Detection**: Identifies and counts anomalies in the training set based on the selected threshold.

