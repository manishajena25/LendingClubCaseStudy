# Lending Club Case Study

### Project Information

> The project is a data science project that uses the lending club data set to predict whether a loan will be defaulted or not.

### Project Background

```
The company, specializing in providing various loans to urban customers, faces a critical decision-making process upon receiving loan applications.

Lending loans to ‘risky’ applicants is the largest source of financial loss
(called credit loss). The credit loss is the amount of money lost by the lender
when the borrower refuses to pay or runs away with the money owed.  

The business objective is to discover patterns that suggest whether an individual is prone to defaulting. This information can guide decisions such as rejecting the loan, adjusting loan amounts, or offering loans to high-risk applicants with increased interest rates, among other actions.  

Perform an analysis to understand the driving factors (or driver variables)
behind loan default, i.e.the variables which are strong indicators of default.  
The company can utilise this knowledge for its portfolio and risk assessment.

```

### Data Set

> The data set is a CSV file(loan.csv) with the loan data for the Lending Club.

## DataSet Analysis

The dataset below provides information about past loan applicants and their 'default' status.
The goal is to discern patterns indicating the likelihood of default, guiding actions like loan denial, amount reduction, or higher interest rates for riskier applicants.
It's important to note that this dataset reflects loans post-approval, offering insights into approved loans only and not the rejection criteria. The primary objective is to identify key leading indicators (driver variables) contributing to defaults, using the analysis as a foundation for hypotheses.
The loan process involves three main steps:
- The potential borrower requests a loan amount.
- The approver approves/rejects an amount based on past history/risk.
- The final amount offered as a loan by the investor.

#### Step 1: Importing the data
#### Step 2: Data Cleaning - Removing the rows having all missing values
#### Step 3: Data Cleaning - Dropping the columns having all null values
#### Step 4: Data Cleaning - Dropping additional columns which we don't need as these are mostly nulls.
#### Step 5: Data Cleaning - Formatting employment length column to have only numbers.
#### Step 6: Data Cleaning - Removing % symbol from interest rate column so that it can be used in calculations.
#### Step 7: Data Cleaning - Deriving some new columns using existing data like creating month and year columns separately
#### Step 8: Derived Metrics Analysis
#### Step 9: Univariate Analysis
#### Step 10: Bivariate Analysis
#### Step 11: Results   

## Glossary
EDA - Exploratory Data Analytics

### Contributor
Manisha Jena







##### This project is inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.
