# Titanic Survival Classification

An end-to-end Machine Learning project completed as part of the **Arch Technologies Data Science Internship (Month 1)**. This project uses passenger data from the historic Titanic disaster to predict whether a passenger would survive or not based on features like age, gender, passenger class, and embarkation point.

## 🚀 Project Overview
* **Objective:** Build a binary classification model to predict passenger survival.
* **Dataset:** Official Titanic Dataset containing demographics and trip information for 891 passengers.
* **Algorithm Used:** Random Forest Classifier.
* **Model Accuracy:** **79.89%**

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Environment:** Google Colab
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn

## 📋 Machine Learning Pipeline
1. **Data Loading:** Imported the raw dataset directly from an online source into a Pandas DataFrame.
2. **Data Cleaning:**
   * Filled missing `Age` values using the median.
   * Handled missing `Embarked` values using the mode.
   * Dropped non-predictive columns (`PassengerId`, `Name`, `Ticket`, `Cabin`).
3. **Feature Engineering:** Encoded categorical features (`Sex` and `Embarked`) into numerical values using mapping and One-Hot Encoding.
4. **Data Splitting:** Divided the data into an 80% training set and a 20% testing set.
5. **Model Training:** Fit a Random Forest Classifier with 100 estimators onto the training data.
6. **Evaluation:** Tested the model using the validation set, generating a complete Classification Report and a Confusion Matrix heatmap.

## 📈 Results
The model achieves a robust baseline performance:
* **Accuracy Score:** 79.89%
* **Precision (Survived):** 0.76
* **Recall (Survived):** 0.74

---
*Completed by Syeda Farah Jaseem Zaidi during Month 1 of the Data Science Internship at Arch Technologies.*
