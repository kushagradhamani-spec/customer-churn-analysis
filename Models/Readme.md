# Models Folder

This folder contains the trained machine learning models and the scaler used for preprocessing features. These models were trained to predict **customer churn** based on historical data.

---

## Files in this folder

| File Name                          | Description                                           |
|-----------------------------------|-------------------------------------------------------|
| `logistic_regression_model.pkl`    | Logistic Regression model trained on the dataset.    |
| `random_forest_model.pkl`          | Random Forest model trained on the dataset.          |
| `scaler.pkl`                       | StandardScaler used to scale features for Logistic Regression. |

---

## How to Use

1. **Load the models and scaler using `joblib`:**

```python
import joblib

# Load models
lr_model = joblib.load('models/logistic_regression_model.pkl')
rf_model = joblib.load('models/random_forest_model.pkl')
scaler = joblib.load('models/scaler.pkl')
