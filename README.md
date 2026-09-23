# Telecom Customer Churn Analysis & Prediction Using AI

**Student:** Yug Jaiswal  
**Program:** AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026 | BharatCares

## Project overview
This project performs an end-to-end telecom customer churn analysis. It covers data cleaning, exploratory data analysis, feature engineering, supervised machine learning, model evaluation, feature importance and AI-assisted business insights.

## Problem statement
Telecom companies need to identify customers who may leave so that retention teams can investigate relevant service and customer-experience factors. The project builds a reproducible analytics pipeline to understand churn patterns and predict churn risk.

## Dataset
The project uses the public **IBM Telco Customer Churn** sample dataset. IBM describes the dataset as fictional telecommunications customer data and defines `Churn` as whether the customer departed within the last month.

Dataset source:
https://github.com/IBM/telco-customer-churn-on-icp4d/blob/master/data/Telco-Customer-Churn.csv

Direct CSV used by the notebook:
https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

IBM documentation:
https://www.ibm.com/docs/en/cognos-analytics/12.1.x?topic=samples-telco-customer-churn

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Classification / predictive analytics

## Project workflow
1. Load dataset
2. Inspect data types, missing values and duplicates
3. Clean `TotalCharges`
4. Explore churn by contract, tenure, payment method and services
5. Engineer interpretable features
6. Build Logistic Regression and Random Forest models
7. Evaluate Accuracy, Precision, Recall, F1 and ROC-AUC
8. Visualize confusion matrix and ROC curve
9. Analyze Random Forest feature importance
10. Generate AI-assisted, rule-based business insights

## How to run

### 1. Create an environment
```bash
python -m venv venv
```

Windows:
```bash
venv\Scripts\activate
```

macOS/Linux:
```bash
source venv/bin/activate
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Open the notebook
```bash
jupyter notebook YugJaiswal_TelcoCustomerChurn.ipynb
```

### 4. Run all cells
The notebook first checks for `Telco-Customer-Churn.csv` in the same folder. If it is not found, it loads the public IBM CSV URL.

## Expected project outputs
The notebook generates:
- Churn distribution chart
- Churn rate by contract
- Churn rate by tenure
- Churn rate by payment method
- Monthly-charge summary
- Model comparison table
- Classification report
- Confusion matrix
- ROC curve
- Random Forest feature-importance chart
- Segment-level churn tables
- AI-assisted retention insights

## Important interpretation note
A predictive relationship is not automatically a causal relationship. The model is intended to prioritize customers and identify patterns for further investigation, not to claim that a single feature causes churn.

## Files
- `YugJaiswal_TelcoCustomerChurn.ipynb` — complete project code
- `requirements.txt` — required Python packages
- `YugJaiswal_TelcoCustomerChurnReport.docx` — project report
- `README.md` — project overview and setup instructions
