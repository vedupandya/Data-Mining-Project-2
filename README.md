# Data-Mining-Project-2

## Group Members
- Kalhar Patel (202101009)
- Vedant Pandya (202101063)
- Suyash Bhagat (202101085)
- Dhyey Vachhani (202101190)
- Jalp Patel (202101267)

## DATASET: Credit risk analysis

## Project Summary: 

In our project we did the following:
- There were 73 columns and many of them had a large amount of null entries so we couldn't simply drop them. Therefore, we replaced the null values in some columns with the median of the respective column.
- Label Encoding and transforming: There were many categorical features, so we used Label Encoding in preprocessing for the ordinal categorical columns. There were some other non-numeric columns (e.g date) so we transformed them in numeric (e.g duration).
- Visualization: We visualized the distribution of some important features using histograms and count plots.
- Creating New Features: We created 3 new features by combining other features to yield more useful ones.
- Correlation Plot and Feature Selection
- Model Selection and Training: We trained two types of classification models, Logistic Regression and Random Forest Classifier. The data was severly imbalanced so we trained the models on the normal dataset and a balanced dataset formed through oversampling.
- Model Tuning: We tuned the model using GridSearchCV based on the f1-score metric.
- Evaluation: We evaluated the models based on Accuracy, Precision, Recall and ROC-AUC score.

## Possible Problems on the Dataset:
 
- Loan Default Prediction:
  Problem: Predicting whether a loan will default or not based on various features, including loan amount, interest rate, borrower's annual income, loan grade, purpose, and other relevant information.
  Application: Helping lenders assess the creditworthiness of borrowers, make informed lending decisions, and manage risk.
- Loan Payment Behavior Prediction:
  Problem: Predicting the payment behavior of borrowers (e.g., early payment, on-time payment, late payment) based on historical data.
  Application: Assisting lenders in proactively managing borrower accounts and collections.
- Loan Grade Classification:
  Problem: Classifying loans into different grades (A, B, C, D, E, F, G) based on the provided features.
  Application: Streamlining the loan grading process and automating risk assessment for lenders.
- Loan Purpose Analysis:
  Problem: Analyzing and categorizing loan purposes to identify common trends and patterns in borrower intentions.
  Application: Providing insights to financial institutions for product development and marketing strategies.
- Risk Factor Identification:
  Problem: Identifying the most significant factors contributing to loan default, such as loan amount, interest rate, or annual income.
  Application: Helping lenders mitigate risk by focusing on the most critical risk factors in their lending decisions.
- Borrower Income Classification:
  Problem: Classifying borrowers into income brackets based on their annual income.
  Application: Tailoring financial services and offers to different income groups and demographic segments.
- Loan Status Classification:
  Problem: Classifying loans into different categories of loan status (e.g., Current, Late, Fully Paid, Defaulted).
  Application: Monitoring and managing the loan portfolio to ensure timely payments and minimize default rates.
- Loan Installment Analysis:
  Problem: Exploring the relationship between loan installments and loan default, and potentially predicting the optimal installment amount.
  Application: Helping borrowers choose an installment plan that suits their financial capabilities.

These problems can provide valuable insights into the dataset, help lenders make informed decisions, and improve risk management practices in the lending industry. 

### We chose to tackle Loan Default Prediction, as it is a valuable tool for lenders and financial institutions, as it helps them make informed decisions, manage risk, comply with regulations, and ultimately optimize their lending practices to maximize profitability while minimizing losses due to defaults.

## CONTRIBUTIONS
1) Data Pre-Processing: Vedant Pandya and Kalhar Patel
2) Exploratory Data Analysis (EDA): Vedant Pandya and Kalhar Patel
3) Modeling: Vedant Pandya and Kalhar Patel
4) Documentation: Dhyey Vacchani
