# 🔮 Customer Churn Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict customer churn using various machine learning models. By analyzing customer behavior and historical data, the project identifies patterns that influence customer retention and provides insights for businesses to take proactive measures.

## 🚀 Features
- Data preprocessing, including handling missing values, encoding categorical variables, and scaling numerical data.
- Comparison of multiple machine learning models:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - XGBoost
  - LightGBM
  - CatBoost
- Hyperparameter tuning using **GridSearchCV** to optimize model performance.
- Feature engineering for better predictive accuracy.
- Model evaluation using accuracy, precision, recall, F1-score, and ROC-AUC.

## 🛠️ Tools & Technologies
- **Python**
- **Jupyter Notebook**
- **Pandas & NumPy** - Data manipulation and preprocessing.
- **Scikit-Learn** - Model training and evaluation.
- **XGBoost, LightGBM, CatBoost** - Advanced boosting algorithms.
- **Matplotlib & Seaborn** - Data visualization.

## 📂 Files Included
- 📜 `churn-prediction-using-machine-learning.ipynb` - Jupyter Notebook with the complete analysis and implementation.
- 📊 **Dataset**: `churn.csv` - Contains customer data for churn prediction.

## 📈 Dataset Information
- **Columns:**
  - `CustomerID`: Unique identifier for each customer.
  - `Gender`: Male/Female.
  - `SeniorCitizen`: Binary indicator (0 = No, 1 = Yes).
  - `Partner`: Whether the customer has a partner (Yes/No).
  - `Dependents`: Whether the customer has dependents (Yes/No).
  - `Tenure`: Number of months the customer has stayed with the company.
  - `PhoneService`: Whether the customer has phone service (Yes/No).
  - `MultipleLines`: Whether the customer has multiple phone lines (Yes/No/No phone service).
  - `InternetService`: Type of internet service (DSL, Fiber optic, None).
  - `OnlineSecurity`: Whether the customer has online security (Yes/No/No internet service).
  - `OnlineBackup`: Whether the customer has online backup (Yes/No/No internet service).
  - `DeviceProtection`: Whether the customer has device protection (Yes/No/No internet service).
  - `TechSupport`: Whether the customer has tech support (Yes/No/No internet service).
  - `StreamingTV`: Whether the customer has TV streaming service (Yes/No/No internet service).
  - `StreamingMovies`: Whether the customer has movie streaming service (Yes/No/No internet service).
  - `Contract`: Type of contract (Month-to-month, One year, Two year).
  - `PaperlessBilling`: Whether the customer uses paperless billing (Yes/No).
  - `PaymentMethod`: Customer's payment method (Electronic check, Mailed check, Bank transfer, Credit card).
  - `MonthlyCharges`: The amount charged to the customer monthly.
  - `TotalCharges`: The total amount charged to the customer.
  - `Churn`: The target variable (Yes/No) indicating whether the customer churned.

## 📈 Model Performance
- **Key Metrics:**
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC
