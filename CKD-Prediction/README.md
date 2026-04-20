# Chronic Kidney Disease Prediction

## Overview
This project applies machine learning techniques to predict **Chronic Kidney Disease (CKD)** using clinical and laboratory data.

Two modeling approaches are compared:
- **Diagnostic setting** → uses full clinical and laboratory variables  
- **Screening setting** → removes key diagnostic indicators to simulate early-stage detection  

---

## Methods

### Model Development
- Implemented supervised learning models (e.g., Logistic Regression, Random Forest)
- Applied models to structured medical data for CKD prediction

### Data Processing
- Performed **Exploratory Data Analysis (EDA)**
- Handled missing values using imputation strategies

### Model Selection & Optimization
- Used **nested cross-validation** for robust model selection  
- Fine-tuned hyperparameters of the best-performing model  

### Model Diagnostics
- Analyzed the **bias–variance trade-off**  
- Used **learning curves** and **validation curves** to assess generalization  

### Evaluation
- Evaluated performance using confusion matrix–based metrics:
  - **Recall (Sensitivity)**
  - **Specificity**
  - **F1-score**

---

## Key Insight
Reducing feature availability (screening scenario) leads to lower predictive performance, highlighting the trade-off between **early detection** and **diagnostic accuracy**.

---

## Tech Stack
- Python
- scikit-learn
- pandas
- matplotlib
