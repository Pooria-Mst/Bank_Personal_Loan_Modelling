

The dataset, "Bank Personal Loan Modelling", contains 14 columns and 5000 entries. Here is a brief explanation of its structure and potential target:

Key Columns:
ID: Unique identifier for each record.
Age: Age of the customer.
Experience: Work experience in years.
Income: Annual income of the customer (in thousands).
ZIP Code: ZIP code of the customer’s residence.
Family: Number of family members.
CCAvg: Average monthly credit card spending.
Education: Education level (1 = Undergraduate, 2 = Graduate, 3 = Advanced/Professional).
Mortgage: Amount of mortgage.
Personal Loan (Target Variable): Indicates whether the customer accepted a personal loan offer (0 = No, 1 = Yes).
Securities Account: Binary indicator for owning a securities account (0 = No, 1 = Yes).
CD Account: Binary indicator for owning a certificate of deposit account (0 = No, 1 = Yes).
Online: Binary indicator for using online banking (0 = No, 1 = Yes).
CreditCard: Binary indicator for having a credit card with the bank (0 = No, 1 = Yes).
Objective:
The target column is Personal Loan, which represents whether a load assignment is required (1 = Yes) or not (0 = No). 
The goal is to predict this variable based on other factors in the dataset. Key predictors may include Income, CCAvg, Education, and other financial indicators.
