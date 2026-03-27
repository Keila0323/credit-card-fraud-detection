credit-card-fraud-detection
Exploratory analysis of 284,000+ credit card transactions to uncover fraud patterns using Python and Pandas.

Overview
This project analyzes a real-world credit card transaction dataset to identify patterns associated with fraudulent activity. It focuses on understanding class imbalance, exploring transaction behavior, and highlighting statistical signals that differentiate legitimate transactions from fraud—skills directly relevant to risk monitoring and financial data analysis roles.

Project Goals
Load and explore a large-scale financial transaction dataset (284,000+ records).

Quantify and visualize the extreme class imbalance between fraudulent and legitimate transactions.

Identify statistical patterns and anomalies in transaction amounts, frequency, and key features.

Visualize fraud distribution and risk indicators using clear, readable charts.

Summarize insights in a way that supports practical fraud risk decisions.

Tools & Technologies
Programming: Python (Pandas, NumPy, Matplotlib, Seaborn if used)

Environment: VS Code (or Jupyter Notebook, if applicable)

Techniques: Data cleaning and transformation, exploratory data analysis (EDA), basic statistical analysis, data visualization

Dataset
Source: Credit Card Fraud Detection — Kaggle (MLG-ULB)

Size: 284,807 transactions, 492 fraud cases, 30 anonymized features

Characteristics: Highly imbalanced dataset where fraud represents roughly 0.17% of all transactions, reflecting real-world fraud detection challenges.

Key Findings
Approximately 73.6% of fraudulent transactions are under 100 units in amount, suggesting deliberate “card testing” behavior before higher-value purchases.

Fraudulent transactions have an average amount of about 122.21 compared with 88.29 for legitimate ones, a difference of roughly 38%.

Fraud cases appear across the full transaction timeline without clear peak hours, indicating that simple time-based detection rules may not be effective on their own.

(You can adjust the numbers or wording if you refine your analysis.)

How to Run
Clone the repository

bash
git clone https://github.com/Keila0323/credit-card-fraud-detection.git
cd credit-card-fraud-detection
Set up the environment

Python 3.9+ recommended

Install dependencies (if you do not have a requirements.txt, list the packages in the README or create one):

bash
pip install pandas numpy matplotlib seaborn
Download the dataset

Go to the Kaggle dataset page: “Credit Card Fraud Detection — MLG-ULB”.

Download creditcard.csv and place it in the project root (or in a data/ folder if your script/notebook expects that path).

Run the analysis

Open credit_card_fraud_analysis.py in VS Code and run the script, or

If you have a notebook version, open it in Jupyter and run all cells in order.

View results

Plots and summary statistics will display in your environment.

If the script saves figures or tables, they will appear in the designated outputs/ or similar folder (you can mention the exact folder once you set it).

Future Improvements
Build and evaluate a simple classification model (e.g., logistic regression, random forest) to predict fraud.

Experiment with resampling techniques (SMOTE, undersampling, oversampling) to address class imbalance.

Add more advanced evaluation metrics (precision, recall, F1-score, ROC–AUC) tailored to fraud detection.

Package the analysis into a reusable notebook or dashboard for non-technical stakeholders.

About the Author
Data science student at Northeastern University with over 12 years of experience in financial services, including fraud monitoring, risk analysis, and banking operations. This project combines hands-on analytics in Python with real-world domain expertise in detecting anomalies in financial transaction data.
🔗 [LinkedIn](#) | [GitHub Profile](https://github.com/Keila0323)
