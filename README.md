# 🫁 Lung Cancer Histopathology Image Classification using Modified ResNet50

A deep learning project that classifies lung histopathology images into multiple cancer categories using a modified ResNet50 architecture with transfer learning. The project focuses on improving feature representation through customized classification layers and advanced preprocessing techniques.



## Project Overview

This project implements an end-to-end deep learning pipeline for multiclass lung cancer histopathology image classification. A pretrained ResNet50 model is fine-tuned with a custom dual-path classification head to learn discriminative features from microscopic tissue images.

The pipeline includes stain normalization, image augmentation, transfer learning, model fine-tuning, and comprehensive performance evaluation.



## Key Features

- Transfer Learning using Modified ResNet50
- Custom Dual-Path Classification Head
- Stain Normalization for Histopathology Images
- Data Augmentation for Improved Generalization
- Two-Stage Fine-Tuning Strategy
- Comprehensive Model Evaluation
- End-to-End Deep Learning Pipeline



## Dataset
The dataset used is : LC25000
The model is trained to classify histopathology images into the following classes:

- Lung Adenocarcinoma (Lung ACA)
- Lung Squamous Cell Carcinoma (Lung SCC)
- Normal Lung Tissue





## Technologies Used

### Programming
- Python

### Deep Learning
- TensorFlow
- Keras

### Machine Learning
- Scikit-learn

### Computer Vision
- OpenCV

### Data Processing
- NumPy
- Pandas

### Visualization
- Matplotlib

### Development Environment
- Google Colab



## Workflow

1. Data Loading
2. Image Preprocessing
3. Stain Normalization
4. Data Augmentation
5. Transfer Learning with ResNet50
6. Custom Classifier Construction
7. Model Training
8. Fine-Tuning
9. Performance Evaluation



## Evaluation Metrics

The trained model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- Classification Report
