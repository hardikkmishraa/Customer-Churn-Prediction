# Customer Churn Prediction

## 📋 Project Overview

Complete machine learning pipeline for predicting telecom customer churn using the **Telco Customer Churn dataset** (7,043 customers × 20 features).

**Target**: Binary classification - Churn (Yes/No)

**Distribution**: 73.5% retained (5,174), 26.5% churned (1,869)

## 📊 Dataset

`textFeatures: gender, SeniorCitizen, tenure, MonthlyCharges, TotalCharges, 
          Contract, PaymentMethod, PhoneService, InternetService, etc.
Key Stats:
- Tenure: 0-72 months (mean: 32.37)
- MonthlyCharges: $18.25-$118.75 (mean: $64.76)
- TotalCharges: $0-$8684.80 (mean: $2279.73)`

## 🛠️ Pipeline Implemented

1. **Data Cleaning**: Fixed 11 missing TotalCharges (blanks → 0.0, converted to float)
2. **EDA**: Univariate, bivariate analysis completed
3. **Preprocessing**:
    - Label encoded 16 categorical columns
    - Target encoded (Churn: Yes=1, No=0)
4. **Next Steps**: Model training, evaluation, deployment

## 🚀 Quick Start

`bash# Google Colab ready
pip install pandas scikit-learn xgboost matplotlib seaborn
# Open: Customer_churn.ipynb`

## 📈 Key Insights

`text✅ Data loaded & explored (shape: 7043×20)
✅ Missing values treated (11 TotalCharges)
✅ Categorical encoding complete (16 columns)
✅ Class imbalance identified (26.5% churn)
🔄 Model training ready`

## 📁 File Structure

`textCustomer_churn.ipynb      # Complete analysis pipeline
data/                     # Dataset (if saved locally)
results/                  # Visualizations & metrics`

## 🎯 Business Value

**Identifies at-risk customers** for targeted retention:

- Month-to-month contracts
- High monthly charges
- Short tenure customers

**Status**: EDA & preprocessing complete, ready for modeling!

---

*Machine Learning - Pandas - Scikit-learn - XGBoost - Google Colab*
