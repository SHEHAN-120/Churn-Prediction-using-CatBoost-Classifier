# Customer Churn Prediction using CatBoost Classifier

This project aims to predict customer churn using the **CatBoost Classifier** on a structured dataset. It involves the complete machine learning pipeline including data preprocessing, model training, and performance evaluation.

## 🗂 Dataset

The dataset used is `churn_modelling.csv`. It contains features like customer demographics, credit score, tenure, balance, and more, helping predict whether a customer will leave the bank (churn).

## ⚙️ Machine Learning Pipeline

### 1. Data Preprocessing

* Handled missing values.
* Deal with categorical variables
* Split the dataset into **training** and **testing** sets.

### 2. Model Building & Training

* Used **CatBoostClassifier** for training due to its high performance with categorical data and lower need for preprocessing.
* Tuned hyperparameters using built-in settings for faster convergence.

### 3. Evaluation

* Evaluated model using:

  * **Confusion Matrix**
  * **Accuracy Score**

These metrics helped assess how well the model distinguishes between churned and non-churned customers.

## 📊 Results

The model showed strong performance in identifying customer churn based on the available features, indicating its reliability in practical use cases.


