# Customer Churn Prediction System

## Project Overview

This project develops a Machine Learning system to predict customer churn using the IBM Telco Customer Churn dataset. It analyzes customer information and compares two classification algorithms to identify customers who are likely to leave a telecom service.

## Problem Statement

Customer churn is a major challenge for telecommunications companies. Predicting which customers are likely to leave can help businesses improve customer retention and make data-driven decisions.

## Dataset

- **Dataset:** IBM Telco Customer Churn
- **Total Records:** 7,043
- **Total Original Features:** 21
- **Target Variable:** `Churn`
- **Target Classes:** Yes / No

Dataset source:

[IBM Telco Customer Churn Dataset](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Project Workflow

1. Load the telecom customer churn dataset.
2. Perform Exploratory Data Analysis (EDA).
3. Identify and handle missing values.
4. Convert `TotalCharges` into numeric format.
5. Encode categorical features using one-hot encoding.
6. Encode the target variable.
7. Split the dataset into training and testing sets.
8. Scale numerical features using StandardScaler.
9. Train Logistic Regression and K-Nearest Neighbors (KNN) models.
10. Evaluate both models using classification metrics and confusion matrices.
11. Compare model performance and analyze overfitting.

## Machine Learning Models

### 1. Logistic Regression

A classification algorithm used to predict whether a customer is likely to churn.

### 2. K-Nearest Neighbors (KNN)

A distance-based classification algorithm that predicts customer churn based on nearby data points.

## Model Evaluation Results

| Metric | Logistic Regression | KNN |
|---|---:|---:|
| Accuracy | 80.55% | 76.30% |
| Precision | 65.72% | 55.38% |
| Recall | 55.88% | 55.08% |
| F1-Score | 60.40% | 55.23% |

## Key Findings

- Logistic Regression achieved better results across all four evaluation metrics.
- Logistic Regression showed nearly identical training and testing accuracy (80.55%).
- KNN achieved 83.42% training accuracy and 76.30% testing accuracy.
- The training/testing accuracy gap in KNN suggests possible overfitting.
- Logistic Regression demonstrated more consistent generalization on the test data.

## How to Run the Project

1. Open the project notebook in Google Colab.
2. Upload or load the IBM Telco Customer Churn dataset.
3. Run all notebook cells in sequence.
4. Review the EDA visualizations, evaluation metrics, and confusion matrices.

## Project Deliverables

- Jupyter Notebook containing the complete ML workflow.
- Model evaluation results.
- Data visualization and confusion matrices.
- Project report.
- This README documentation.

## Conclusion

The project demonstrates an end-to-end customer churn prediction workflow using Python and Machine Learning. Logistic Regression performed better than KNN on the test dataset and showed more consistent training and testing accuracy.

**Note:** Final notebook execution and deliverable verification are pending.
