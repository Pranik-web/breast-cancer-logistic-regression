# Breast Cancer Prediction using Logistic Regression

## Project Overview

This project develops a supervised machine learning model using **Logistic Regression** to classify breast tumors as **Benign (Non-Cancerous)** or **Malignant (Cancerous)** based on medical diagnostic measurements.

The project demonstrates the complete machine learning workflow, including data preprocessing, feature scaling, model training, prediction, and evaluation.


## Problem Statement

Breast cancer is one of the most common cancers worldwide. Early detection plays a significant role in improving treatment outcomes.

The objective of this project is to build a binary classification model that predicts whether a breast tumor is **Benign (B)** or **Malignant (M)** using features extracted from breast mass images.

## Dataset

**Dataset:** Breast Cancer Wisconsin Diagnostic Dataset

**Target Variable**

 Diagnosis - Meaning

B - Benign (Non-Cancerous) 
M - Malignant (Cancerous) 

After preprocessing:

- **0 → Benign**
- **1 → Malignant**

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Algorithm

**Logistic Regression**

### Why Logistic Regression?

- Suitable for binary classification problems.
- Predicts the probability of a sample belonging to one of two classes.
- Simple, fast, and easy to interpret.
- Provides a strong baseline model for medical diagnosis classification tasks.

---

## Project Workflow

1. Import required libraries
2. Load the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Check for missing values
5. Remove unnecessary columns
6. Encode the target variable
7. Visualize class distribution
8. Separate features and target
9. Split the dataset into training and testing sets
10. Apply feature scaling using StandardScaler
11. Train the Logistic Regression model
12. Make predictions on the test dataset
13. Evaluate model performance

---

## Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns (`id`, `Unnamed: 32`)
- Converted diagnosis labels:
  - Benign → 0
  - Malignant → 1
- Split dataset into training and testing sets
- Standardized features using StandardScaler

> **Note:** Feature scaling was performed **after** splitting the dataset to prevent data leakage.

---

## Model Evaluation

The model was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report

### Model Performance

**Accuracy:** **97%**

Classification Report

| Class | Precision | Recall | F1-Score |
|--------|----------:|-------:|---------:|
| Benign (0) | 0.97 | 0.99 | 0.98 |
| Malignant (1) | 0.98 | 0.95 | 0.96 |

---

## Project Structure

```
Breast-Cancer-Prediction/
│
├── Breast_Cancer_Logistic_Regression.ipynb
├── archive.zip
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Scaling
- Binary Classification
- Logistic Regression
- Model Evaluation
- Supervised Machine Learning
- Scikit-learn

---

## Future Improvements

- Decision Tree Classification
- Random Forest Classification
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Hyperparameter Tuning
- Cross Validation
- Model Deployment using Flask or Streamlit

---

## Key Learning Outcomes

Through this project, I learned how to:

- Build a complete supervised machine learning pipeline.
- Preprocess real-world datasets.
- Prevent data leakage by applying feature scaling after train-test splitting.
- Train a Logistic Regression classifier.
- Evaluate classification performance using multiple metrics.
- Understand how machine learning models can be used to predict outcomes for new, unseen data




Aspiring Machine Learning & AI Engineer
