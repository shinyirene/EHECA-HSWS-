# EHECA-HSWS-
EHECA-HSWS framework for menstrual health monitoring using AI/ML
Overview

The Ensemble Hybrid Extreme Convolutional Autoencoder-based Harbor Seal Whisker Search (EHECA-HSWS) model is designed for menstrual health monitoring using AI and machine learning techniques. This model leverages a combination of XGBoost, Swin Transformer, Hybrid CNN, Autoencoders, and the Harbor Seal Whiskers Optimization Algorithm (HSWOA) for enhanced predictive accuracy and anomaly detection.

Features

User Segmentation: Uses XGBoost for clustering users based on menstrual patterns.

Issue Extraction: Swin Transformer extracts key issues from user feedback.

Pattern Tracking: Hybrid CNN tracks menstrual health variations.

Anomaly Detection: Autoencoder identifies irregularities in menstrual cycles.

Hyperparameter Optimization: HSWOA optimizes the model’s parameters.

Performance Evaluation: Analyzes accuracy, precision, recall, and F1-score.
Dataset Description

The English Menstrual Health and Hygiene chatbot dataset is utilized to compute the EHECA-HSWS model’s performance for analyzing user behavior and feedback data to improve the user experience during menstruation. This dataset is available at:
Menstrual Health Dataset (https://www.kaggle.com/datasets/shafaqfatimamughal/english-menstrual-health-and-hygiene-chatbot)

This dataset contains a variety of information, including demographics, behavior data, feedback, and menstruation-related data. It includes details on age, gender, and location to identify preferences among different groups of users. Certain age groups have distinct needs during menstruation, while location data reveals regional variations in behavior and preferences.

Additionally, the dataset includes:

App or platform interactions during menstruation

Usage frequency and session duration

Types of content accessed

In this research, 80% of the data is used for training, and 20% is used for testing to ensure model generalization.

Model Workflow

Data Collection: Wearable devices collect menstrual health indicators.

Preprocessing: Standardization and feature selection.

Training:

XGBoost for segmentation.

Swin Transformer for issue extraction.

Hybrid CNN for health tracking.

Autoencoder for anomaly detection.

HSWOA for hyperparameter tuning.

Prediction: Generates menstrual health insights.

Evaluation: Accuracy, Precision, Recall, and F1-score computation.
