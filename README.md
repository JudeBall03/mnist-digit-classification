# mnist-digit-classification
Comparison of machine learning models for handwritten digit classification using the MNIST dataset

---

## Overview

This project investigates the performance of various machine learning models on the MNIST handwritten digit dataset.

The dataset consists of 70,000 grayscale images (28x28 pixels) representing digits from 0–9.

---

## Models Implemented

- Logistic Regression
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- Support Vector Machines (Linear & RBF)
- Decision Tree
- Random Forest
- Feedforward Neural Network
- Convolutional Neural Network (CNN)

---

## Key Findings

- CNN achieved the highest accuracy (~99%) but required significant training time
- Random Forest provided the best balance between accuracy (~96.6%) and efficiency
- Simpler models (e.g. QDA) struggled with visually similar digits

---

## Methodology

1. Data split into training, validation, and test sets  
2. Standardisation of pixel values  
3. PCA applied (retaining 95% variance) for selected models  
4. Model training and evaluation using:
   - Accuracy
   - F1-score
   - Training time  
5. Confusion matrices used for error analysis  

---

## How to Run

1. Clone the repository  
2. Open the notebook in Jupyter  
3. Ensure required Python packages are installed  
4. Run all cells to reproduce the results  

---

## Tech Stack

- Python  
- scikit-learn  
- NumPy / pandas  
- Matplotlib / seaborn  
- Neural networks (TensorFlow / PyTorch if used)

---

## Summary

This project demonstrates the trade-off between model performance and computational efficiency, highlighting when simpler models may outperform more complex approaches in practical settings.
