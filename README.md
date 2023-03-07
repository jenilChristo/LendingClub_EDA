## Lending club case study 

![Lending club](https://github.com/jenilChristo/LendingClub_EDA/blob/main/loandata.png?raw=true)




Lending club a finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision


## About  
- The borrowers who default cause the largest amount of loss to the lenders, reduces lender’s cash flow. Identifying those risky applicants helps in cutting down the amount of credit loss to the organization. The data set used is 'loan.csv'.

    • If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

    • If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

- The Objective of this study is to find the driving factors behind loan default, for the company to assess its risk and portfolio management


## Conclusions
* Higher interest rate (13-22%)
* Employees with experience more than 10+ years contribute to loan defaults more followed by year 6, 7, 8 and 9 .
* Interest rate greater than 16 % and the annual income of the person is less than 100000
* DTI ratio more than 13 and interest rate is higher than 15%
* Loan defaulting increases with increase in public bankruptcy records.
* Borrowers with mortgaged home and rented home default more than people with own home.
* Housing loans with higher interest rate (above 9 %)
* Loan amount to income ratio contributes to loan defaults
* Grades F, G and H are the top contributors of loan defaults
* Shorter loan tenure (36 months)
* State AK, MT, KY, UT, TN borrowed marginally above the 10k level median 13k and contribute to defaults.
* Debt consolidation, credit card and small business are the top loan purpose that contribute to defaults
* Loan amount to income ratio higher than .5 contributes to loan defaults
* Verified loan amounts are given to employee with good experience and they tend to default.
* Verified loans with high loan amount for borrowers with mortgage and rental homes
* Installments increase with higher loan amount and so is the defaulting rate


## Technologies Used
- Python - version 3.10
- NumPy - version 1.24.1
- Pandas - version 1.5.2
- Matplotlib - version 3.6.3
- Seaborn - version 0.12.2


## References
- This project was created as a case study required for Executive PG Programme in Machine Learning & AI - IIIT, Bangalore
- References:
    - [Reference - 1](https://www.liebertpub.com/doi/10.1089/big.2018.0092)