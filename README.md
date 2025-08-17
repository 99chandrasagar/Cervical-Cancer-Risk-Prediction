# Cervical Cancer Risk Prediction

This repository contains the implementation of **Machine Learning models** for predicting the likelihood of a positive biopsy diagnosis for cervical cancer based on anonymized patient risk factor data.

---

## 📌 Problem Statement
Cervical cancer is one of the most preventable and treatable forms of cancer when detected early through proper screening and risk assessment.  
In developing regions, late-stage detection due to lack of access to healthcare services often leads to higher mortality rates.  

The objective is to build ML models that can predict the likelihood of cervical cancer using **demographic, behavioral, medical history, and diagnostic test results**.

---

## 📊 Dataset
- **File:** `risk_factors_cervical_cancer.csv`  
- **Samples:** 858 women  
- **Target Variable:** `Biopsy`  
  - `0` → No cervical cancer  
  - `1` → Cancer detected  

### Features
- **Demographic:** Age, number of sexual partners, pregnancies  
- **Behavioral:** Smoking, contraceptive use  
- **Medical history:** STDs, HPV infection  
- **Diagnosis results:** Hinselmann, Schiller, Citology, Biopsy  

---

## 🛠️ Workflow

### 1. Data Exploration
- Loaded dataset and libraries
- Sanity check (first 2 rows)
- Data visualization & correlation analysis

### 2. Data Preprocessing
- Missing values handling
- Outlier detection & treatment
- Feature engineering
- Standardization / Normalization
- Feature importance analysis

### 3. Model Building
- Train/Test split (80:20 and other ratios)
- Models implemented:
  - Logistic Regression
  - Decision Tree
  - K-Nearest Neighbour (KNN)
  - Ensemble Method (Random Forest / Bagging / Boosting)
- Hyperparameter tuning using Cross-Validation

### 4. Evaluation
- Metrics: Precision, Recall, F1-Score, AUC-ROC
- Performance comparison chart
- Best model identification with justification

---

## 📈 Results
- Performance comparison of all models
- Selected **best performing model** for cervical cancer prediction
- Justification for chosen model

---

## 🚫 Restrictions
- **Deep Learning models are not allowed**  
- Only classical ML techniques are implemented  

---
