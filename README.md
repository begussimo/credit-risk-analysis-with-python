# Credit Risk Analysis with Python

In this project, an analysis of the most significant factors influencing Home Loans has been conducted. HomeBank financial company operates in Urban, Semiurban, and Rural areas, and they employ application forms for mortgage applications as part of their working model. These forms collect essential customer information, including Gender, Marital Status, Education, Number of Dependents, Income, and Loan Amount.

The main focus of this project was to examine the impact of these factors on the approval status of Loan/Mortgage applications.

### Hypothesis Generation

1. Salary : Applicants with higher income  should have higher approval rates on the loans
2. Credit History : Applicants with better credit history should have higher approval rates on the loans
3. Loan Amount : Applicant with lower loan amount application should have higher approval rates on the loans

### Univariate Analysis

In this analysis, each variable in the dataset analysed individually to understand their impact on loan approvals. The results are represented in the graphs :

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Loan_Status.jpeg)

This graps show us that out of 614 applications, 422 of them has been approved.

When it comes to variables like Gender, Martial Status, Credit History, each of these variables has been analysed individually to understand dataset more in detail.

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Unvariate%20Analysis.jpeg)

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Unvariate%20Analysis2.jpeg)

Density distribution analysis of Applicant Income and Loan Amount has been performed also to understand income distribution of the population and also box plot analysis to understand the outliers better .

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Density.jpeg)


![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Density2.jpeg)

### Bivariate Analysis

To test the hypothesis that has been created in the begining, the comparision of individual variable with the target variables will be performed to understand their effect on the loan approval better.

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Bivariate1.png)

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Bivariate2.png)

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Bivariate3.png)

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Bivariate4.png)

And the rest of the analysis will be more towards income related bivariate analysis with loan status. How the applicant,coapplicant,total income would affect the loan approval status.

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Bivariate5.jpeg)

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Bivariate6.jpeg)

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Bivariate7.jpeg)

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Bivariate8.jpeg)

As it can bee seen from above graphs, the variables like credit history, total income, property area and load amount has the biggest impact on the approval rate of the loan.

### Correlation between the numerical variables

Heatmaps can be used to colorize the data variations and demonstrate their relationships. 

![alt text](https://github.com/begussimo/credit-risk-analysis-with-python/blob/main/images/Corr.jpeg)

As it can be seen from the heatmap, the most corrolated values are Applicant income-Loan Amount and also Credit History-Loan Status.
