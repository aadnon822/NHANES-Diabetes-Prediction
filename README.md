# NHANES-Diabetes-Prediction
Diabetes prediction using NHANES 2021–2022 data with ML models, SHAP explanations, and reproducible notebooks.

# Early Detection of Diabetes Using Machine Learning (NHANES 2021–2022)

This project predicts diabetes status based on U.S. health survey data using multiple machine learning models (Logistic Regression, Random Forest, XGBoost).

## Structure
- `notebooks/`: Preprocessing, EDA, model training, SHAP
- `data/`: Raw and cleaned datasets
- `models/`: Exported `.pkl` files
- `reports/`: SHAP plots, metrics, and whitepaper
- `scripts/`: Utility code (e.g., XPT to CSV)

## Results
- Best AUC: 0.87 (XGBoost)
- Feature Importance: HbA1c, Glucose, BMI, Waist, Calories

## Setup
```bash
pip install -r requirements.txt
