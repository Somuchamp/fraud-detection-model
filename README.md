# Fraud Detection Model – Financial Transactions

This project uses machine learning models (Logistic Regression, Random Forest, XGBoost) to detect fraudulent transactions in a dataset of 6M+ rows.  

### Key Highlights
- Data cleaning, handling missing values, and balancing classes using SMOTE.
- Achieved ROC-AUC ≈ 0.99 with Random Forest and XGBoost.
- Key predictors of fraud: `errorBalanceOrig`, `newbalanceOrig`, `TRANSFER`, `CASH_OUT`.

### Tech Stack
- Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn, Jupyter Notebook

### Results
The model successfully identified fraudulent transactions with high precision and recall, despite severe class imbalance (fraud ≈ 0.11% of total transactions).
