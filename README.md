# 📉 Customer Churn Prediction with MLflow

This project predicts customer churn for a telecom company using logistic regression and logs the full pipeline with MLflow.

## 🔍 Dataset
**Telco Customer Churn Dataset**  
🔗 [Download here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

- Features: services used, customer demographics, monthly charges, tenure, etc.
- Target: `Churn` (Yes/No)

## 🧠 ML Pipeline
- Cleaned missing values & converted categorical data
- Encoded target labels & scaled numerical features
- Trained Logistic Regression model
- Tracked parameters, metrics, and artifacts using MLflow

## 🛠️ Tools Used
- scikit-learn
- pandas, numpy, matplotlib
- MLflow (for MLOps lifecycle)
- joblib (for saving models)

## 📈 Results
- Achieved ~80% accuracy
- Used classification report and confusion matrix to validate results

## ⚡ How to Run
Run the notebook `churn_prediction_mlflow.ipynb` in Google Colab or Jupyter Lab with MLflow installed.
