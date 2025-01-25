# Demonstrating Enhanced Accuracy with Bayesian Logistic Regression

## Overview

This project investigates the use of **Bayesian methods** for cancer prediction, specifically for classifying breast tumors as malignant or benign. The dataset used is the **Wisconsin Breast Cancer** dataset, which contains features derived from digitized images of breast masses. This work leverages **Bayesian Ridge Regression** for feature selection and **Bayesian Logistic Regression** for tumor classification, comparing the performance of Bayesian models to standard Logistic Regression. The Bayesian approach offers a significant advantage by providing uncertainty quantification in predictions, which is crucial for medical decision-making.

The project aims to:
- Use Bayesian Ridge Regression to select the most relevant features, reducing dimensionality and improving the focus on informative variables.
- Apply Bayesian Logistic Regression to classify the tumors, and compare the results with traditional Logistic Regression models.
- Quantify uncertainty in the model predictions to enhance interpretability and reliability, which is particularly valuable in healthcare applications.

### Key Features
- **Bayesian Ridge Regression**: Reduces dimensionality and identifies the most relevant features using prior information and uncertainty.
- **Bayesian Logistic Regression**: Classifies breast tumors with Bayesian inference, providing uncertainty quantification in predictions.
- **Model Comparison**: Compares the performance of Bayesian Logistic Regression with standard Logistic Regression to highlight the benefits of the Bayesian approach.
- **Uncertainty Quantification**: Provides insights into the reliability of the predictions using posterior distributions, a critical aspect in medical decision-making.
- **Evaluation Metrics**: Measures model performance using accuracy, precision, recall, and the area under the ROC curve (AUC).

## Technologies Used
- **Programming Languages**: Python
- **Libraries/Frameworks**: scikit-learn, NumPy, pandas, Matplotlib, PyMC3 (or similar for Bayesian inference)
- **Dataset**: Wisconsin Breast Cancer Dataset
