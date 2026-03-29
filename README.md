![Fraud vs Legitimate Transactions](chart1_fraud_vs_legit.png)

# Credit Card Fraud Detection

EDA of 284,000+ credit card transactions to understand fraud patterns using Python and Pandas.

## Overview

Analyze a real-world credit card dataset to:
- Explore transaction behavior and class imbalance.
- Highlight patterns that separate fraudulent and legitimate transactions.
- Practice risk-focused data analysis relevant to fraud monitoring roles.

## Project Goals

- Explore 284,807 credit card transactions and 30 anonymized features.
- Quantify and visualize the extreme class imbalance (~0.17% fraud).
- Analyze transaction amounts, time, and key features for fraud signals.
- Create clear charts that communicate risk to non-technical audiences.

## Tech Stack

- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** VS Code  
- **Methods:** Data cleaning, EDA, basic statistics, visualization  

## Dataset

- **Source:** [Credit Card Fraud Detection — Kaggle (MLG-ULB)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- 284,807 transactions · 492 fraud cases · 30 features  

## Key Findings

- 73.6% of fraudulent transactions are under 100 units → likely “card testing” behavior.
- Fraudulent transactions average 122.21 vs 88.29 for legitimate ones (~38% higher).
- Fraud occurs throughout the timeline with no strong peak hours, so simple time rules are weak on their own.

## How to Run

```bash
git clone https://github.com/Keila0323/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install pandas numpy matplotlib seaborn
```

1. Download `creditcard.csv` from the Kaggle link above.  
2. Place it in the project folder (same level as `credit_card_fraud_analysis.py`).  
3. Run:

```bash
python credit_card_fraud_analysis.py
```

4. Open the generated `.png` charts to view the results.

## Future Work

- Add a simple model (logistic regression / random forest).
- Try resampling methods (SMOTE, undersampling, oversampling).
- Evaluate with precision, recall, F1-score, and ROC–AUC.
- Turn the analysis into a small dashboard or report.

## About

Data science student at Northeastern University with 12+ years in financial services (fraud monitoring, risk, and banking operations).

[GitHub Profile](https://github.com/Keila0323)
🔗 [LinkedIn](#) | [GitHub Profile](https://github.com/Keila0323)
