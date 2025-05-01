# Diabetes Prediction using Machine Learning

This project focuses on applying machine learning classification models to predict the onset of diabetes based on diagnostic measurements from the Pima Indians Diabetes Dataset.

## Project Description

The goal was to build and evaluate models that can accurately predict whether a patient is likely to develop diabetes. The project involved standard machine learning steps including data preprocessing, model training, and performance evaluation using various metrics suitable for binary classification.

## Domain

Healthcare / Binary Classification

## Key Techniques & Skills Demonstrated

* **Data Preprocessing:** Handling Missing Values (using imputation), Feature Scaling (using StandardScaler).
* **Classification:** Implementation and comparison of different classification algorithms:
    * Gaussian Naive Bayes
    * Support Vector Machine (SVM) with Radial Basis Function (RBF) kernel
    * Support Vector Machine (SVM) with Linear kernel
* **Model Evaluation:** Comprehensive evaluation using:
    * Accuracy Score
    * Confusion Matrix
    * Precision, Recall, F1-score (from Classification Report)
    * Receiver Operating Characteristic (ROC) Curve and Area Under the Curve (AUC).
* **Data Splitting:** Used `train_test_split` with stratification for reliable evaluation.
* **Libraries:** `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`.

## Dataset

Pima Indians Diabetes Dataset. Features include health metrics (e.g., Glucose, BMI, Insulin) and the target is a binary outcome (Diabetes Positive/Negative).

## Outcome

Successful implementation and evaluation of multiple classification models, demonstrating the process of applying machine learning for medical prediction tasks and comparing different algorithmic approaches based on relevant evaluation metrics.

## Project Context

This project was completed as coursework for the **Data Mining (CAS764)** course during the **Master of Science (M.Sc.) in Computer Science** program at the **Department of Computer Applications, National Institute of Technology, Tiruchirappalli** in **Spring 2016**, under the guidance of **Prof. Ramadoss**.
