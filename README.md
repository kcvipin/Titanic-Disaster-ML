# Titanic Survival Prediction – Machine Learning Pipeline

## 📌 Project Overview

This project builds an end-to-end **machine learning pipeline** to predict passenger survival in the **Titanic disaster**, using the classic Kaggle Titanic dataset.  
It covers **data exploration, feature engineering, model training, hyperparameter tuning, ensemble learning, and final prediction generation**.

The notebook follows a **systematic, experiment-driven approach** commonly used in real-world ML workflows and Kaggle competitions.

---

## 📂 Dataset

- **Source:** Kaggle – Titanic: Machine Learning from Disaster  
- **Files used:**
  - `train.csv` – Training data with labels (`Survived`)
  - `test.csv` – Test data without labels

---

## 🔧 Libraries & Tools

- **Data Analysis & Visualization**
  - numpy
  - pandas
  - matplotlib
  - seaborn

- **Machine Learning**
  - scikit-learn
  - xgboost

---

## 🧠 Workflow Breakdown

### 1️⃣ Data Loading & Merging
- Training and test datasets are loaded and combined for consistent feature engineering.
- A `train_test` flag is used to separate data later.

### 2️⃣ Exploratory Data Analysis (EDA)
- Numerical feature analysis (Age, Fare, SibSp, Parch)
- Categorical feature analysis (Sex, Pclass, Embarked, Cabin, Ticket)
- Correlation analysis and visualization

### 3️⃣ Feature Engineering
- Cabin-based features
- Ticket-based features
- Title extraction from names
- One-hot encoding for categorical variables

### 4️⃣ Data Preprocessing
- Missing value handling
- Feature scaling using StandardScaler
- Train-test split preparation

---

## 🤖 Models Implemented

- Gaussian Naive Bayes  
- Logistic Regression  
- Decision Tree  
- K-Nearest Neighbors (KNN)  
- Random Forest  
- Support Vector Classifier (SVC)  
- XGBoost Classifier  

All models are evaluated using **cross-validation**.

---

## ⚙️ Hyperparameter Tuning

- GridSearchCV
- RandomizedSearchCV
- Model-specific optimization

---

## 🧩 Ensemble Learning

- Hard Voting Classifier
- Soft Voting Classifier
- Weighted Voting Classifier
- Voting combined with XGBoost

---

## 📤 Output

Multiple Kaggle-ready submission files are generated in the format:

PassengerId, Survived

---

## 📈 Key Highlights

- Strong feature engineering focus
- Multiple model comparison
- Ensemble learning techniques
- Portfolio-grade ML project

---

## 🚀 How to Run

1. Clone the repository  
2. Install dependencies  
3. Add Titanic dataset files  
4. Run the notebook end-to-end  
