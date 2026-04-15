# Customer Churn / Classification with Dashboard (ML Project)

## Overview
This project builds a machine learning classification system with database integration, data preprocessing, model training, explainability, and an interactive dashboard. It is designed to predict binary outcomes using structured business data.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, XGBoost, Imbalanced-learn (SMOTE), SHAP, SQLAlchemy, MySQL, Dash, Plotly

## Key Features
- Database integration using SQLAlchemy and MySQL  
- Data preprocessing using pipelines and column transformers  
- Missing value handling using SimpleImputer  
- Feature scaling and encoding  
- Handling class imbalance using SMOTE  
- Model building using Logistic Regression and XGBoost  
- Hyperparameter tuning using RandomizedSearchCV  
- Model explainability using SHAP  
- Interactive dashboard using Dash and Plotly  
- Customer segmentation using KMeans clustering  

## Models Used
- Logistic Regression  
- XGBoost Classifier  
- KMeans Clustering (segmentation)

## Workflow
1. Data extraction from database  
2. Data cleaning and preprocessing  
3. Feature engineering  
4. Handling class imbalance using SMOTE  
5. Model training and evaluation  
6. Explainability using SHAP  
7. Dashboard development using Dash  

## Evaluation
The model was evaluated using:
- Confusion Matrix  
- Classification Report  
- ROC-AUC Score  

Note: The ROC-AUC score is approximately 0.50, indicating the model currently performs at baseline level. The issue is very likely not the model or SMOTE — it’s the signal in the data.

## Dashboard
An interactive Dash-based dashboard is built for:
- Data exploration  
- Prediction visualization  
- Business insights  

## Run
git clone https://github.com/Shirls-0913/ai-telecom-churn-prediction-platform/blob/main/PM_PR_0017_NoChurn_Telecom_Churn_Prediction.ipynb  

## Output
- Classification predictions  
- Model performance metrics  
- SHAP feature importance plots  
- Interactive dashboard  
