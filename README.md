**Task 1:**
**Creditworthiness Prediction Using Logistic Regression**

This repository contains a simple implementation of a machine learning model to predict creditworthiness based on financial data. The project demonstrates the use of Logistic Regression for binary classification and evaluates its performance using accuracy, confusion matrix, and classification report metrics.

**Key Features**

Dataset: A simulated dataset with features such as age, income, loan amount, and credit history.
Model Training: Logistic Regression is used to classify individuals as creditworthy or not.
Performance Evaluation: The model is evaluated on a test set with detailed metrics including accuracy, precision, recall, and F1-score.

**Steps in the Code**

Dataset Creation:
A simulated dataset is generated with features representing financial and credit data.
Data Preprocessing:
Features (age, income, loan_amount, credit_history) are separated from the target (creditworthy).
Train-Test Split:
The data is split into training and testing sets (70-30 split).
Model Training:
Logistic Regression is used to train the model on the training dataset.
Model Evaluation:
Predictions are made on the test set, and metrics like accuracy, confusion matrix, and classification report are generated to assess model performance.

**Results**

The output includes:
Model accuracy on the test set.
A confusion matrix showing true/false positives and negatives.
A detailed classification report including precision, recall, and F1-score for each class.




**Task 2 : Disease Prediction Using Random Forest Classifier**


This repository contains an implementation of a machine learning model to predict the likelihood of a disease based on symptoms, age, and smoking history. The project demonstrates the use of Random Forest Classifier, a robust ensemble learning technique, for binary classification and evaluates its performance using multiple metrics.

**Key Features**

Dataset: A simulated dataset with features such as fever, cough, age, smoking history, and a target column indicating disease presence.
Model Training: A Random Forest Classifier is trained to predict whether a patient is likely to have a disease.
Feature Encoding: Categorical variables like smoking history are encoded into numerical format.
Feature Scaling: Standard scaling is applied to improve model performance.
Performance Evaluation: The model's accuracy, confusion matrix, and detailed classification report are used for assessment.


**Steps in the Code**

Dataset Preparation:
A sample dataset is created with features representing patient symptoms and medical history.
Data Preprocessing:
LabelEncoder encodes categorical variables (e.g., "smoking history").
StandardScaler scales numerical features to normalize data.
Train-Test Split:
The data is divided into training (70%) and testing (30%) sets.
Model Training:
A Random Forest Classifier with 100 estimators is trained on the scaled training dataset.
Model Evaluation:
Predictions are made on the test set, and metrics like accuracy, confusion matrix, and classification report are generated to assess performance.

**Results**

The output includes:
Accuracy: The percentage of correct predictions.
Confusion Matrix: Details true/false positives and negatives.
Classification Report: Includes precision, recall, and F1-score for each class.
