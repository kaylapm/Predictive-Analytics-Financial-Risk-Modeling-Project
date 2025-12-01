# 📊 Predictive Analytics & Financial Risk Modeling  
### *Python-Based Machine Learning Project*

This project focuses on building predictive models for **financial risk assessment** using two real-world Kaggle datasets: **Lending Club Loan** and **Home Credit Default Risk**. The goal is to compare multiple machine learning algorithms and identify the optimal model for predicting loan repayment risks.

---

## 🚀 Project Overview
The project includes the full machine learning workflow:
- Data preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Handling class imbalance  
- Model training  
- Performance evaluation  
- Model comparison using 10-fold cross-validation

This project was completed as part of the *Predictive Modeling and Analytics* coursework.

---

## 📂 Datasets
Two Kaggle datasets were used:

1. **Lending Club Loan — Kaggle**  
2. **Home Credit Default Risk — Kaggle**

Each dataset contains borrower credit history, demographic information, financial behavior, and loan repayment outcomes.

---

## 🛠️ Tech Stack
- **Python 3.x**
- **Libraries Used:**
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - `imbalanced-learn`
  - `xgboost` (optional)

---

## 🔧 Workflow & Methods

### 1️⃣ Data Preprocessing
- Handling missing data  
- Outlier detection & removal  
- Feature encoding (Label Encoding / One-Hot Encoding)  
- Feature scaling  
- Stratified train-test splitting (75% train, 25% test)

### 2️⃣ Handling Class Imbalance
- SMOTE oversampling  
- Random undersampling  
- Class weighting adjustments  

### 3️⃣ Exploratory Data Analysis (EDA)
- Distribution plots  
- Correlation matrix  
- Feature importance inspection  

---

## 🤖 Machine Learning Models
The following models were implemented and compared:

- **k-Nearest Neighbors (k-NN)**
- **Naïve Bayes**
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Tree Classifier**
- **Backpropagation Neural Network**

Each model was evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- AUC ROC  
- **10-Fold Cross Validation**

---

## 🏆 Results Summary
Model performance was compared using average cross-validation scores.  
The evaluation identified the most optimal model for financial risk prediction based on **AUC ROC** and **balanced classification metrics**.

(You may insert tables / images of charts here.)

---

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/kaylapm/Predictive-Analytics-Financial-Risk-Modeling-Project.git
cd financial-risk-modeling
