# LOAN_ELIGIBILITY_PREDICTION

# Overview

1. Loan Eligibility Prediction is a machine learning project aimed at determining whether a loan applicant is eligible for a loan based on various attributes such as income, employment status, loan amount, and credit history.
2. The goal is to build a predictive model that assists financial institutions in streamlining the loan approval process.


# Features
1. The dataset used for this project includes the following features:
2. Gender: Male or Female
3. Married: Marital status of the applicant
4. Dependents: Number of dependents
5. Education: Education level (Graduate/Not Graduate)
6. Self_Employed: Employment status
7. ApplicantIncome: Applicant's income
8. CoapplicantIncome: Co-applicant's income
9. LoanAmount: Loan amount applied for
10. Loan_Amount_Term: Loan repayment term in months
11. Credit_History: Credit history (1 indicates a good history, 0 indicates bad)
12. Property_Area: Urban, Semi-Urban, or Rural
13. Loan_Status: Target variable (Y/N indicating approval)

# Steps
1. Data Preprocessing
  Handling Missing Values: Missing values in features such as Gender, Dependents, and Credit_History are filled with the mode value.
  Encoding Categorical Variables: Categorical variables are encoded into numerical formats suitable for modeling using techniques like label encoding.
2. Exploratory Data Analysis (EDA)
  Distribution of features is visualized using box plots, histograms, and bar charts.
  Relationships between features and the target variable are analyzed to identify significant predictors.

# Results
1. Models achieved high accuracy in predicting loan eligibility.
2. Credit history, income, and loan amount were identified as significant predictors.
