# Lending Club Case Study
> A Case study to identify if a borrower is eligible to pay-off the loan amount and interest, and for the bank to make informed decision wheather to approve or reject a loan application based on the outcomes of the analysis. Perform EDA on the data set to arrive at a conclusion for the problem statement.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Perform exploratory data analysis on a data set of loan accounts by Lending Club 
- This project aims to find a pattern or indicator that can be used as a key indicator to grant or reject a loan request such that the lender does not reject a borrower who can fully pay the loan thus losing good business and approve loan application where the borrower does not pay the loan and defaults, thus leaving the company at a loss and a bad business.
- The purpose of this analysis is to find strong indicators and patterns in the data set of borrower accounts and identify potential defaulters.
- The data set contains loan accounts that are:
    -  Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
    -  Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
    -  Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

## Conclusions
- Upon purpose vs loan status analysis - it is concluded that loans for "small business" have a significant risky of being "charged off" or default on their loan.
- Loan accounts having grade 'F' and 'G' have high liklihood of defaulting on thier loan.
- Sub-grades of 'F' and 'G' have a considerably higher likelihood of being charged off.
- People who's Home Ownership status as "OTHER" are show to be more likely to default (charge off) their loan.
- Loan accounts having higher "Revolving Credit Utilisation" rate are more likely to be a defaulter.
- Most cases of defaulter are seen to have a loan duration of "60 months"
- It is also observed that loan accounts (borrowers) who have a debt to income ratio under "35%" are more likely to pay off their loan amount

## Technologies Used
- matplotlib - version 3.3.4
- numpy - version 1.20.1
- pandas - version  1.2.4
- seaborn - version 0.11.1

## Acknowledgements
- Investopedia for explanation on DTI - https://www.investopedia.com/terms/d/dti
- OnDeck for Insights on revolving credit - https://www.ondeck.com/resources/dont-mess-up-your-fico-score-manage-your-revolving-credit-usage#:~:text=50%25%20to%2075%25%3A%20This,more%20reasonable%20to%20a%20lender.

## Contact
Created by [@ayushsaxena210] - reach out to me! 
Created by [@RezonChakraborty] - feel free to contact me!