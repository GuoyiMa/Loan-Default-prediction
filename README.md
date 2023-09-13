# Loan-Default-prediction

# 1. Project introduction
This project is based on the background of personal credit in financial risk control, and requires predicting whether there is a possibility of default based on the data information of the loan applicant, so as to decide whether to approve the loan.

# 2. Dataset Description

## 2.1 Overview
The data comes from the loan records of a credit platform, with a total data volume of more than 1 million, including 47 columns of variable information, 15 of which are anonymous variables. Among them, 800,000 records are used as the training set, and 200,000 records are used as the test set A.

## 2.2 Data Dictionary
| Variable | Definition |
| :-----| :----- |
| Id | Unique id of credit identifier assigned to the loan list |
| loanAmnt | loan amount |
| term | Loan term (year) |
| interestRate | Lending rates |
| installment | Installment amount |
| grade | loan grade |
| subGrade | Subclasses of Loan Grades |
| employmentTitle | Employment title |
| employmentLength | Years of employment |
| homeOwnership|Ownership status of the home as provided by the borrower at the time of registration
| annualIncome | Annual income
verificationStatus	| verification Status
issueDate | issue Date
purpose | The loan purpose category of the borrower at the time of the loan application
postCode | The first 3 digits of the postal code provided by the borrower in the loan application
regionCode | region Code
dti | debt-to-income ratio
delinquency_2years | The number of default events overdue for more than 30 days in the borrower's credit file in the past 2 years
ficoRangeLow | The lower limit range of the borrower's fico at the time of loan disbursement
ficoRangeHigh | The upper limit range of the borrower's fico at the time of loan disbursement
openAcc | The number of outstanding credit lines in the borrower's credit file
pubRec | Number of derogatory public records
pubRecBankruptcies | Number of public records expunged
revolBal | Total credit turnover balance
revolUtil | Revolving Facility Utilization
totalAcc | The total number of credit lines currently in the borrower's credit file
initialListStatus | Initial Listing Status of the Loan
applicationType | Indicate whether the loan is an individual application or a joint application with two co-borrowers
earliesCreditLine | The month in which the borrower's earliest reported line of credit was opened
title | The name of the loan provided by the borrower
policyCode | Publicly Available Policy_Code=1 New Product Not Publicly Available Policy_Code=2
n-series anonymous features Anonymous features | n0-n14, processing for counting features for some lender behavior

# 3. Data Exploratory

# 4. Data Preprocessing
## 4.1 Categorical data
## 4.2 Missing data
## 4.3 Outlier

# 5. Modeling
