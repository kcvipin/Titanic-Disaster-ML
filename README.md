# 🚢 Titanic Survival Prediction Model

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-brightgreen.svg)

## 📌 Executive Summary
This project aims to predict passenger survival on the RMS Titanic using machine learning techniques. By analyzing historical passenger data—including demographics, ticket class, and fare information—this notebook explores relationships between variables and builds a predictive model to classify whether a passenger survived the tragedy.

---

## 🛠️ Project Workflow

### 1. Data Acquisition & Understanding
* **Dataset:** Titanic Dataset (Kaggle).
* **Features:** PassengerID, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked.

### 2. Exploratory Data Analysis (EDA)
* Visualized correlations between features and survival rates using `seaborn` and `matplotlib`.
* Identified key factors influencing survival (e.g., Sex, Pclass).

### 3. Data Preprocessing & Feature Engineering
* **Missing Value Imputation:** Handled missing data in 'Age' and 'Embarked' columns.
* **Categorical Encoding:** Converted categorical data (Sex, Embarked) into numerical representations using One-Hot Encoding.
* **Feature Engineering:** Created new features to enhance model predictive power (e.g., Family Size).

### 4. Modeling & Evaluation
* Implemented multiple classification algorithms:
    * Logistic Regression
    * Random Forest Classifier
    * Support Vector Machines (SVM)
* Evaluated models using **Accuracy** and **Confusion Matrices**.

---

## 📊 Key Insights & Results

| Model | Accuracy (Training) |
| :--- | :--- |
| Random Forest | **[XX.X%]** |
| Logistic Regression | [XX.X%] |
| SVM | [XX.X%] |

* **Key Finding:** Passenger gender was the highest predictor of survival.

---

## 🚀 Installation & Usage

### Prerequisites
Ensure you have Python installed and the necessary libraries:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
