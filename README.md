# Lending Club Case Study

### About Lending Club
> Lending Club one of the world's largest peer-to-peer lending platform. It matches borrowers who are seeking for a loan with investors who are looking to lend money in the similar portfolio. It Provides wide variety of loan like personal, business, medical etc

### Problem Statement
> As the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 

> The company may face financial loss in either cases: 
>>If the applicant is likely to repay the loan, but the company is not approving the loan
>>If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan

### Objective
> The objective of the case study is to understand the driving factors/variables behind the loan default i.e., the variables which are strong indicators of default.

### Data Set used
> For this case study we are using loan.csv dataset and also Data_Dictionay.xlsx


So to find the solution for the problem stated above we did some analysis on the given dataset **loan.csv**.




## Conclusions
### Recommendation on the basis of Segmented Univariate Analysis
Conclusion and Recommendation
After analyzing all the multivariate charts, we can clearly observe the potentially strong indicators/ predictors of
loan default. These are following:
➢ annual_inc - The self-reported annual income provided by the borrower during registration.
➢ grade - LC assigned loan grade
➢ last_pymnt_amnt - Last total payment amount received
➢ term - The number of monthly payments on the loan.
➢ int_rate - Interest Rate on the loan
➢ dti - A ratio calculated using the borrower’s total monthly debt divided by the borrower’s self-reported monthly
income.
➢ revol_util - Amount of credit the borrower is using relative to all available revolving credit.

Reason for their selection:
There are few more variables which have shown strong trends with loan default status, however those variables are not as
good indicators as above mentioned variables because these selected variables individually and in combination with each
other, separate the loans with higher default rate and not nullifying their combining impact on loan default rate.
These variables, in together, have increased the degree of separability between loan default or not-default, thus are
potential indicators.
Therefore, achieving the objective of problem statement of Lending Club Case Study.

## Contact
- Akash Agrawal - [@akashwal](https://github.com/akashwal)
- Vishnu Vivek - [@VishnuVivek009](https://github.com/VishnuVivek009)
