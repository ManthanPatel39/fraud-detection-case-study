# fraud-detection-case-study
Fraud detection case study using machine learning on imbalanced financial transaction data.
## Problem Statement
The objective is to build a machine learning model to detect fraudulent transactions and derive actionable business insights for fraud prevention.

## Dataset
- Large transaction dataset with over 6.3 million rows
- Highly imbalanced target variable (`isFraud`)
- Features include transaction type, amount, account balances, and fraud labels

## Project Workflow
1. Data loading and inspection  
2. Missing value and duplicate checks  
3. Exploratory Data Analysis (EDA)  
4. Class imbalance analysis  
5. Feature engineering  
6. Sampling strategy for practical modeling  
7. Model building using Random Forest  
8. Model evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - ROC-AUC
   - Confusion Matrix
   - Precision-Recall Curve
9. Business insights and fraud prevention recommendations

## Model Used
- **Random Forest Classifier**

I selected Random Forest because it performs well on structured tabular data, captures non-linear relationships, and provides feature importance for interpretation.

## Key Highlights
- Performed EDA on the original dataset
- Handled extreme class imbalance using a practical sampling strategy
- Engineered balance-difference features
- Evaluated model with metrics suitable for fraud detection
- Interpreted results in a business context

## Repository Files
- `Fraud Detection.ipynb` → Full notebook solution
## Author
**Manthan Patel**
