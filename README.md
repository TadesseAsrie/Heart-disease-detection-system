# Heart Disease Classification using Machine Learning

This repository contains a machine learning project for predicting the presence of heart disease based on patient clinical parameters[cite: 1]. Developed as a group project for the **Introduction to Machine Learning** course at **Injibara University**, College of Engineering and Technology (Department of Software Engineering)[cite: 1].

---

## 📌 Overview
Heart disease is a leading cause of mortality worldwide[cite: 1]. Early and accurate detection using medical attributes can significantly assist healthcare professionals[cite: 1]. This project evaluates and compares three supervised machine learning algorithms to accurately classify whether a patient has heart disease[cite: 1].

---

## 📊 Dataset Summary
* **Source:** UCI Machine Learning Repository / Kaggle[cite: 1]
* **Instances (Rows):** 1,025[cite: 1]
* **Features (Columns):** 13 medical attributes + 1 target variable[cite: 1]
* **Target Classes:** 
  * `1`: Presence of heart disease[cite: 1]
  * `0`: Absence of heart disease[cite: 1]

---

## 🛠️ Models Implemented
* **Support Vector Machine (SVM)**[cite: 1]
* **Random Forest Classifier**[cite: 1]
* **XGBoost Classifier**[cite: 1]

---

## 📈 Performance & Results
Models were evaluated using an 80/20 train-test split and 5-fold cross-validation[cite: 1]:

| Model | Test Accuracy | Precision | Recall | F1-Score | Mean CV Accuracy |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **SVM** | 81.46%[cite: 1] | 76.38%[cite: 1] | 92.38%[cite: 1] | 83.62%[cite: 1] | 83.51%[cite: 1] |
| **Random Forest** | 100.00%[cite: 1] | 100.00%[cite: 1] | 100.00%[cite: 1] | 100.00%[cite: 1] | **99.71%**[cite: 1] |
| **XGBoost** | 100.00%[cite: 1] | 100.00%[cite: 1] | 100.00%[cite: 1] | 100.00%[cite: 1] | 99.32%[cite: 1] |

> **Best Model:** **Random Forest** was selected as the optimal model due to its high accuracy and cross-validation performance[cite: 1].

---

## 🛠️ Tech Stack & Tools
* **Language:** Python[cite: 1]
* **Environment:** Google Colab[cite: 1]
* **Libraries:** `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`[cite: 1]

---
# if you like the project give me star
