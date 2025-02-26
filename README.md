# Chronic Kidney Disease Prediction Using Machine Learning

## Project Overview
This project aims to predict the presence of **Chronic Kidney Disease (CKD)** using machine learning techniques. The dataset contains various medical attributes related to kidney health, and the goal is to classify patients as **CKD** or **Not CKD** based on these features.

## Dataset Information
- **Dataset Name:** kidney_disease.csv
- **Number of Records:** 400
- **Number of Features:** 26
- **Target Variable:** `classification` (values: `ckd`, `notckd`)

### Features Description:
1. **Numerical Features:**
   - `age` (years)
   - `bp` (blood pressure, mmHg)
   - `bgr` (blood glucose random, mg/dL)
   - `bu` (blood urea, mg/dL)
   - `sc` (serum creatinine, mg/dL)
   - `sod` (sodium, mEq/L)
   - `pot` (potassium, mEq/L)
   - `hemo` (hemoglobin, g/dL)

2. **Categorical Features:**
   - `rbc` (red blood cells, normal/abnormal)
   - `pc` (pus cell, normal/abnormal)
   - `pcc` (pus cell clumps, present/not present)
   - `ba` (bacteria, present/not present)
   - `htn` (hypertension, yes/no)
   - `dm` (diabetes mellitus, yes/no)
   - `cad` (coronary artery disease, yes/no)
   - `appet` (appetite, good/poor)
   - `pe` (pedal edema, yes/no)
   - `ane` (anemia, yes/no)

## Machine Learning Approach
### **Data Preprocessing**
- Handling missing values (imputation using mean/median/mode based on data distribution)
- Encoding categorical variables (One-Hot Encoding or Label Encoding)
- Feature scaling (MinMaxScaler)
- Removing outliers using statistical methods

### **Model Selection**
Several classification models are tested:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. XGBoost Classifier
5. K-Nearest Neighbors (KNN)
6. Support Vector Machine (SVM)
7. Naive Bayes Classifier
8. Voting Classifier (ensemble method)

### **Model Evaluation Metrics**
- Accuracy
- Precision, Recall, F1-Score (from Classification Report)
- Confusion Matrix & Heatmap
## Contribution
Feel free to contribute by opening issues or submitting pull requests.
## Contact
For any queries, contact me sai.subbu.in@gmail.com

---
**Author:** Sai Subba Rao Mahendrakar  
**Date:** 26 February 2025  
