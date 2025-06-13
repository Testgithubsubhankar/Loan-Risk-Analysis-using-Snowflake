# Loan-Risk-Analysis-using-Snowflake
SQL Project

Snowflake: https://app.snowflake.com/auptpzs/yl41052/wFpkam0QLhM#query

Dataset Overview
This dataset is designed to provide a rich source of information for tackling financial fraud. It comprises two interconnected CSV files: loan_applications.csv and transactions.csv.

loan_applications.csv
loan_applications.csv offers a detailed view into individual loan applications, capturing demographic information, financial standing, loan specifics, and the crucial fraud_flag indicating fraudulent applications. This dataset is invaluable for understanding the characteristics that might lead to fraudulent loan requests.

transactions.csv
transactions.csv provides a granular look at customer transaction history, including transaction types, amounts, merchant details, and location. Crucially, it also includes a fraud_flag for individual transactions, enabling the analysis of suspicious spending patterns.

The common customer_id across both files allows for a powerful linkage, enabling researchers and data scientists to build more sophisticated fraud detection systems by combining loan application characteristics with real-time transactional behavior.

Post Summary :

1. Used transactional and loan application data to identify risky borrowers based on behavior patterns like high withdrawals and inconsistent spending.

2. Built risk indicators using SQL in Snowflake, such as loan-to-income ratio, transaction variability, and monthly transaction frequency.

3. Joined customer transaction behavior with loan status to explore approval patterns and suggest lending strategy improvements.

4. Flagged over-leveraged applicants and those with negative cash flow using feature engineering and behavioral segmentation.

5. Demonstrated how banks can enhance credit decisions through data-driven behavioral insights.

