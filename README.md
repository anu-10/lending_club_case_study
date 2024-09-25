# Lending Club Case Study

Lending Club, a consumer finance marketplace that specialises in providing a variety of loans to urban customers, is facing a significant issue in handling the loan approval process. When analysing loan applications, the corporation must make wise decisions to reduce financial losses, which are primarily caused by loans provided to applicants that are deemed "risky."

These financial losses, known as credit losses, happen when borrowers fail to repay their loans or default. Simply put, "charged-off" creditors are liable for the company's most severe losses.
The major goal of this exercise is to assist Lending Club in reducing credit loss. 

## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [Collaborators](#collaborators)

## General Information

### Objectives

- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

- In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Conclusions

- Given that applicants who choose for 60-month loans are more likely to default, the organisation should consider assessing the risk associated with longer-term loans and either limiting the maximum term or modifying interest rates accordingly.

- Because loan applicants from Grades B, C, and D account for the majority of "Charged Off" loans, the company should consider establishing stronger risk assessment and underwriting criteria for applicants in these grades.

- Pay close attention to applicants with Subgrades B3, B4, and B5, as they are more prone to charge off. Additional risk reduction strategies, such as granting lesser loan amounts, should be considered.

- Loan applicants with 10 or more years of experience have a higher likelihood of defaulting. This shows that experience alone may not be an accurate predictor of creditworthiness. The organisation should adopt a more complete credit rating system that considers other risk-related indicators.

- Because debt consolidation is the category with the most loans and the highest default rates, the company should carefully analyse applicants for debt consolidation loans and possibly change interest rates or provide financial counselling services.

- From 2007 to 2011, the number of loan applications increased steadily, indicating market expansion. The organisation may capitalise on this trend by maintaining a competitive advantage in the sector while implementing strong risk management techniques.

- Applicants who live in rented or mortgaged properties are more likely to default. This information can be used during the underwriting process to determine housing stability and its impact on repayment ability.

- Verified loan applicants default more frequently than those who are not verified. The organisation should review its verification process to ensure that it effectively assesses applicant creditworthiness, and make any necessary modifications or adjustments.

## Technologies Used

- [Python](https://www.python.org/) - version 3.12.4
- [Matplotlib](https://matplotlib.org/) - version 3.9.2
- [Numpy](https://numpy.org/) - version 2.0.1
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.2

## Acknowledgements

We would like to thank the Upgrad faculty for assigning this case study to us. Working on this case study was an exciting endeavour for us and we were able to explore and learn a lot about EDA.

## Collaborators

Created by [@anupam_muralidharan](https://www.linkedin.com/in/anupam-muralidharan/) and [@nikhil_patil](https://www.linkedin.com/in/nikhilcpatil/)