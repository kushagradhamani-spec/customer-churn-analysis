# 📝 Jupyter Notebooks

This folder contains Jupyter notebooks for the **Customer Churn Prediction** project.  
Each notebook serves a specific purpose in the data science workflow.

---

## 📂 Notebooks

### 1. `eda.ipynb`
- Purpose: Perform **Exploratory Data Analysis (EDA)** on the churn dataset.
- Key steps:
  - Load and clean the dataset
  - Check for missing values and data imbalances
  - Generate summary statistics
  - Visualize churn patterns with graphs and plots

### 2. `model.ipynb`
- Purpose: Build and evaluate **Machine Learning models** for predicting customer churn.
- Key steps:
  - Data preprocessing (encoding, scaling, splitting train/test sets)
  - Train baseline model (Logistic Regression)
  - Train advanced models (Random Forest, XGBoost)
  - Compare performance using Accuracy, Recall, and ROC-AUC
  - Save best-performing model

---

## ⚡ How to Use
1. Make sure all dependencies are installed:
   ```bash
   pip install -r ../requirements.txt
