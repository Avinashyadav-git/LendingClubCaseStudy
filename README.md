# Lending Club Case Study 

## Introduction

This Case study helps to understand how real business problems are solved using Exploratory Data Analysis (EDA).
It is a practical way to learn how data-driven decisions are made in the business world.

## Goal
Minimise the risk of financial loss when lending money to customers. 

## Business Objectives
This company is the largest online loan marketplace, offering personal, business, and medical procedure loans with lower interest rates through a quick online platform. However, lending to risky borrowers can lead to significant financial loss, known as credit loss, when borrowers default or fail to repay. Identifying these risky applicants can help reduce such losses. The goal of this case study is to use EDA to find the factors that indicate a higher likelihood of loan default, helping the company improve its risk assessment and loan portfolio management.

## Risk Associated with the Problem
 - If an applicant is likely to repay the loan, rejecting their loan request means losing a business opportunity.
 - If an applicant is unlikely to repay the loan, approving their loan could result in a financial loss.


 # Overall approach of the analysis
- Data Understanding
- Data Cleaning and preparing the data for analysis by handling missing values, correcting errors, and transforming variables if necessary.
- Data Visualization and Analysis 
- Conclusion: Summarize the key findings and insights derived from the analysis.


### DataSet Analysis
Columns: 111
Rows: 39717
Missing values: 2263366
Unique values: 416800
Duplicates: 0

### Data Cleaning of Columns and Rows
    - Droping column , which were not adding much information 
    - fixing null values
    - Remove duplicate row
    - Remove the outliers
### Data Visualization and Analysis
 - Univariant Analysis ,
 - Segmented Univariate Analysis 
 - Bivariant Analysis

 ## Conclusion 
- Major Driving factor which can be used to predict the chance of defaulting.
    1. Annual income 
    2. Grades
    3. Employment lenght
    4. Debt to Income ration DTI
    5. Pub_rec_bankruptcies
- Other considerations for 'defaults' :
    1. Burrowers not from large urban cities like california, new york, texas, florida etc.
    2. Burrowers having annual income in the range 50000-100000.
    3. Burrowers with working experience 10+ years.
    4. Burrowers having Public Recorded Bankruptcy.
    5. Burrowers with very high Debt to Income value.
  

