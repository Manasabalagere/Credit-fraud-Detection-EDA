# Credit-fraud-Detection-EDA
## Problem Statement 
## Introduction
This project aims to give you an idea of applying EDA in a real business scenario. In this project, apart from applying the techniques that you have learnt in the EDA module, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

## Business Understanding
The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it to their advantage by becoming a defaulter. Suppose you work for a consumer finance company which specialises in lending various types of loans to urban customers. You have to use EDA to analyse the patterns present in the data. This will ensure that the applicants capable of repaying the loan are not rejected.

When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

## Data
The data given below contains the information about the loan application at the time of applying for the loan.
It contains two types of scenarios:
- The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample,
- All other cases: All other cases when the payment is paid on time.

When a client applies for a loan, there are four types of decisions that could be taken by the client/company):

- Approved: The Company has approved loan Application
- Cancelled: The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client, he received worse pricing which he did not want.
- Refused: The company had rejected the loan (because the client does not meet their requirements etc.).
- Unused offer:  Loan has been cancelled by the client but at different stages of the process.

In this case study, we use EDA to understand how consumer attributes and loan attributes influence the tendency to default.

## Business Objectives

This case study aims to identify patterns which indicate if a client has difficulty paying their instalments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.

## Steps Followed
- Importing required libraries.

-- Reading and understanding the data Application Data -> DATASET 1

- Data inspection and basic sanity check
- Cleaning Data
- Handling Missing values
- Checking for outliers
- Univariate Analysis ->Numeric Variables
- Univariate Analysis ->Categorical Variables
- Bivariate Analysis ->Numeric-Numeric
- Bivariate Analysis ->Categorical-Categorical
- Bivariate Analysis ->Numeric-Categorical
- Finding Correlation

-- Reading and understanding the data Previouis Application Data -> DATASET 2

- Data inspection and basic sanity check
- Cleaning Data
- Handling Missing values
- Checking for outliers
- Univariate Analysis ->Numeric Variables
- Univariate Analysis ->Categorical Variables
- Bivariate Analysis ->Numeric-Numeric
- Bivariate Analysis ->Categorical-Categorical
- Bivariate Analysis ->Numeric-Categorical
- Finding Correlation
- Multivariate Analysis

-- Merging the 2 datasets

- Data inspection and basic sanity check
- Univariate Analysis ->Checking for imbalance in data
- Univariate Analysis ->Numeric Variables
- Bivariate Analysis 
- Multivariate Analysis
- Handling Outliers

# Dataset
This dataset has 3 files as explained below: 
1. 'application_data.csv'  contains all the information of the client at the time of application.
The data is about whether a client has payment difficulties.
2. 'previous_application.csv' contains information about the client’s previous loan data. It contains the data on whether the previous application had been Approved, Cancelled, Refused or Unused offer.
3. 'columns_description.csv' is data dictionary which describes the meaning of the variables.

## Details of files given

Details of files given
- Credit Fraud Detection EDA.ipynb : The python commented file showing coding and data analysis including detailed comments.

- Credit Fraud Detection EDA PPt.pdf : Final Presentation to present the Exploratory Data Analysis.
