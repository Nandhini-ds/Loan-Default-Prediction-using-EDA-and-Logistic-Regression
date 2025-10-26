# Loan-Default-Prediction-using-EDA-and-Logistic-Regression

## About Aerofit
LoanTap is an online platform that delivers customized loan products to millennials. It provides instant and flexible loans on consumer-friendly terms to salaried professionals and business owners. Through their innovative approach, LoanTap stands out from the traditional, dull loan segment.

## Business Problem
As a data scientist, I built LogisticRegression model using available features to determine the creditworthiness of applicants. The model predicts whether an applicant is eligible for a loan, and if eligible, recommends the most suitable loan term.

## Dataset
Dataset link: https://drive.google.com/file/d/1ZPYj7CZCfxntE8p2Lze_4QO4MyEOy6_d/view?usp=sharing

## Columns

| Feature | Description |
|---------|-------------|
| `loan_amnt` | The listed amount of the loan applied for by the borrower. If the credit department reduces the loan amount, it is reflected here. |
| `term` | Number of payments on the loan (months). Possible values: 36 or 60. |
| `int_rate` | Interest rate on the loan. |
| `installment` | Monthly payment owed by the borrower if the loan originates. |
| `grade` | LoanTap assigned loan grade. |
| `sub_grade` | LoanTap assigned loan subgrade. |
| `emp_title` | Job title supplied by the borrower. |
| `emp_length` | Employment length in years (0–10; 0 means <1 year, 10 means ≥10 years). |
| `home_ownership` | Home ownership status provided by the borrower or from credit report. |
| `annual_inc` | Self-reported annual income provided by the borrower. |
| `verification_status` | Income verification status: verified, not verified, or source verified. |
| `issue_d` | Month in which the loan was funded. |
| `loan_status` | Current status of the loan – Target variable. |
| `purpose` | Loan category provided by the borrower. |
| `title` | Loan title provided by the borrower. |
| `dti` | Debt-to-income ratio: total monthly debt payments divided by self-reported monthly income (excluding mortgage and LoanTap loan). |
| `earliest_cr_line` | Month when borrower’s earliest credit line was opened. |
| `open_acc` | Number of open credit lines. |
| `pub_rec` | Number of derogatory public records. |
| `revol_bal` | Total revolving credit balance. |
| `revol_util` | Revolving line utilization rate. |
| `total_acc` | Total number of credit lines in the borrower’s credit file. |
| `initial_list_status` | Initial listing status of the loan: W or F. |
| `application_type` | Individual or joint application with two co-borrowers. |
| `mort_acc` | Number of mortgage accounts. |
| `pub_rec_bankruptcies` | Number of public record bankruptcies. |
| `Address` | Address of the individual. |

