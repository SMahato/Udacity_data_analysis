# Identifying Good and bad loans
## by Sumit K Mahato


## Dataset

> The dataset consists of 113937 observations and 81 variables. However, for this analysis I will be considering only 20 variables. The dataset was acquired from Prosper loan database hosted on amazon. It could be found here https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.
The dataset variable definition could be found here https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0


## Summary of Findings

> Following observations were made:

1. Non-Home owners are slightly more likely to default or get charged off
2. It can be noted that the chance of a loan being paid off increases with the income range which is expected. 
3. On the basis of employment status it is interesting to note that the borrowers whose status is not available or not defined properly and falls in other category has the highest chance of defaulting and getting charged off respectively. Therefore, getting details on employment status is one of the most important factors in risk analysis.
4. Default probability is pretty high for a 36 months term whereas 60 months term has the highest charged off percentage.
5. Green Loans(12) are the riskiest in terms of being charged off and has quite a significant default rate. However, Personal loan(4) has the highest default rate.


## Key Insights for Presentation

> On plotting, credit scores on borrower APR we found that there were quite a few borrowers who had high credit scores yet they got loans at high APR. Since, Total Inquiries is the next strongly correlated variable to BorrowerAPR. Plotting it against credit scores we find that there are few high credit score borrowers who has high number of inquiries. These inquiries earns them High APR and eventually they default.
