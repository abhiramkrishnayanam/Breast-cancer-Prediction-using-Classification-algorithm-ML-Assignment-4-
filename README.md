
# Breast Cancer Detection using Classification Techniques

## Overview
This project aims to predict whether a breast cancer tumor is malignant or benign using various classification techniques. The dataset used in this project is the built-in **Breast Cancer Wisconsin** dataset from **scikit-learn**, which contains features derived from digitized images of breast cancer biopsies.

## Dataset
The dataset consists of 30 features that describe characteristics of the cell nuclei present in the breast cancer biopsies. These features include:
- Mean radius
- Mean texture
- Mean perimeter
- Mean area
- Mean smoothness
- Mean compactness
- Mean concavity
- Mean concave points
- Mean symmetry
- Mean fractal dimension
- And others...

The target variable is binary:
- **0** for benign tumors
- **1** for malignant tumors

## Classification Techniques Used
The following classification models were used to predict whether the tumor is malignant or benign:
1. **Logistic Regression**: A statistical model that uses the logistic function to model the probability of a binary outcome.
2. **K-Nearest Neighbors (KNN)**: A non-parametric method that classifies a data point based on the majority class of its k nearest neighbors.
3. **Support Vector Machine (SVM)**: A supervised learning algorithm that finds the optimal hyperplane to separate classes.
4. **Random Forest Classifier**: An ensemble method that builds multiple decision trees and combines their predictions.
5. **Decision Tree Classifier**: A tree-like structure where each internal node represents a feature, each branch represents a decision, and each leaf node represents a class label.

## Key Steps
1. **Data Loading**: The dataset is loaded using scikit-learn's built-in dataset.
2. **Data Preprocessing**:
   - Splitting the dataset into training and testing sets.
   - Standard scaling of features to normalize the dataset.
3. **Model Training**: Each classifier is trained on the training dataset.
4. **Model Evaluation**:
   - Evaluate each model using accuracy, confusion matrix, and classification report.
5. **Comparison**: Compare the performance of the different classification models to determine the best performing model for breast cancer detection.

## Results
- The accuracy of each classifier is calculated.
- The confusion matrix and classification report are used to analyze precision, recall, F1-score, and other important metrics for each model.

## Conclusion
This project demonstrates the application of multiple classification techniques in predicting breast cancer tumor type. Among the classifiers tested, the best performing model is identified, and insights are drawn from the results.

## Requirements
- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
