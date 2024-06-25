# Lending Club 
> Lending Club Project details: The consumer finance company which specialises in lending various types of loans to urban customers.
>
> Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
>
> The main objective to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
>
> Perform an analysis to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company want to utilise this knowledge for its portfolio and risk assessment.  


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contributors](#contributors) 

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Project Information
- This project is a data science project. It uses Lending Club data set to predict whether a loan will be defualted or not.
### Project Background
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures.
- Borrowers can easily access lower interest rate loans through a fast online interface.
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss).
- Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.
- In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Business Problem to solve
- To identify about risky loan applicants, so that such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
  
### Project dataset
- The dataset is a csv file with name: loan.csv. It is added in the repo.


## Conclusions
### Univariate Analysis
- The number of defualted loan is 6 times less than the number of fully paid loan.
- The number of 36 month term loan is 3.5 times higher than 60 months loans, It shows that peolple are taking more loan for sorter duration.
- People have taken most of loan with 5 to 7.5 and 10 to 15 percent Interest Rate.
- People are mostly belongs to 10 years of employment. It shows that these people are most capable to take loans.
- Loans are taken by mostly lower income(20000 to 90000) group people.
- Most of the loans are with grade A and B grades. It means people taking higher grade loans.
- Mostly loans are taken by the people, those don't own Home and they are on Mortgage or Rent.
- 50 % of people and above are verified by lending company or source verified.
- Most of people are taking loan for either credit card and dept consolidation.
- Majority of the people don't have any public record for Bankruptcy
- Majority of the people have very large dept compared to their income. Mostly having 8 to 22 DTI ratio.
- It is showing that loan count is increasing towards year ends. As year progress, loan counts increase in every month compare to last month.
- It is showing that loan approval increasing exponential rate. Increasing every year compare to previous year.
### Bivariate Analysis
- Income group having income 50000 and less are more likely to default than higher income groups.
- As Interest Rate of loan increases default ratio for loans is also increasing.
- The employees having 10+ years of experiance are less likely to default and higher chance to fully paid the loans.
- It shows that the Grade A(Sub Grade) has higher risk and the Grade(Sub Grade) G has lower risk. We can say higher grade(Sub Grade) has higher rate of default and lower grade(Sub Grade) has lower rate of default.
- Fully Paid and Charged Off are almost same for 25% but Charged Off is getting higher after 50% and above than Fully Paid. It means higher the loan amount higher chances of getting defaulted.
- People are making defaulter with Loan amount 10000 and less with None Home ownership. So, Bank should avoid giving loan these people.

### Driving factors which can be used to predict about chances of loan default are:
- Income group
- Interest Rate
- Grade
- Home ownership
- DTI

## Technologies Used
- Numpy - version '1.23.5'
- Pandas - version '1.5.3'
- Seaborn - version '0.12.2'
- Matplotlib - version '3.7.1'

## Acknowledgements
- This project was inspired by UpGrad(IIITB) in AI/ML Executive Post Graduate course as a case study
- This project was based on (https://learn.upgrad.com/course/5800/segment/50366/308501/935805/4670514).

## Contributors
- Ravi Shankar Kushwaha
- Boorsu Ramu

## Contact
Created by [@RavishankarDuMCA10] - feel free to contact me!

