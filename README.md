# Customer Churn Prediction Project

## Project Overview
This project predicts customer churn for a telecommunications company using machine learning. The goal is to identify customers likely to cancel their subscription.

## Dataset
The IBM Telco Customer Churn dataset containing information about:
- 7,043 customers
- 21 features including demographic info, services subscribed, account information
- Target variable: Churn (Yes/No)

## Methodology
1. Data preprocessing and cleaning
2. Exploratory Data Analysis (EDA)
3. Handling class imbalance using SMOTE
4. Training multiple ML models: Logistic Regression, Decision Tree, Random Forest, Neural Network
5. Model evaluation and selection

## Results
The Random Forest model performed best with:
- Accuracy: 0.79
- Precision: 0.67
- Recall: 0.54
- F1-score: 0.60
- ROC-AUC: 0.84

## Key Findings
- Customers with month-to-month contracts have highest churn rate
- Fiber optic internet users are more likely to churn
- Electronic check payers have higher churn probability
- Longer tenure customers are less likely to churn

## Files in this Repository
- `customer_churn_prediction.ipynb` - Complete Colab notebook
- `churn_model.pkl` - Trained model
- `scaler.pkl` - Feature scaler
- `feature_names.json` - Feature names
- `model_performance.csv` - Model evaluation results
- `requirements.txt` - Python dependencies

## How to Run
1. Install requirements: `pip install -r requirements.txt`
2. Open the Jupyter notebook
3. Run all cells to reproduce the analysis

## Author
[D NEHARIKA]
