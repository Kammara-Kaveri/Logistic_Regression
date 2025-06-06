# Logistic_Regression
Integer number is identified from the given image using Logistic Regression

## Logistic Regression for Multiclass Classification (Digits Dataset)
## Overview
This project implements Logistic Regression for multiclass classification using the digits dataset from scikit-learn. It trains a model to classify handwritten digits (0-9), evaluates its performance, and visualizes the confusion matrix using a heatmap.

## Dataset
- **Source:** sklearn.datasets.load_digits
- ### Description:
Contains 1797 samples of 8x8 images of handwritten digits (0-9), with 64 features (pixel values) and 10 classes.
- ### Attributes:
- **digits.data:** Feature matrix (1797 samples, 64 features).
- **digits.target:** Labels (0-9).
- **digits.images:** Raw 8x8 images.

## Code Description
- Loads the digits dataset and visualizes the first 5 images.
- Splits data into training (80%) and testing (20%) sets using train_test_split.
- Trains a Logistic Regression model on the training data.
- Evaluates the model, achieving a test accuracy of 0.9639.
- Predicts the first 5 samples: [0, 1, 2, 3, 4].
- Generates a confusion matrix and visualizes it using a seaborn heatmap.

## Requirements
- Python 3.x
- **Libraries:**
     - scikit-learn (pip install scikit-learn)
     - matplotlib (pip install matplotlib)
     - seaborn (pip install seaborn)
     - numpy (comes with scikit-learn)

## How to Run
1. Clone the repository: git clone <https://github.com/Kammara-Kaveri/Logistic_Regression>
2. Install the required libraries: pip install -r requirements.txt (or manually install as above).
3. Run the script: python digits_classification.py

## Files
- **digits_classification.py:** Main script with the code.
- **README.md:** This file.

## Results
- **Model Accuracy:** 0.9639 on the test set.
- **Confusion Matrix:** Visualized as a heatmap, showing correct and incorrect predictions for each digit class.

