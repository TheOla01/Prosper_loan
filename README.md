**This dataset is financial dataset and this is related to the loan, borrowers, lenders, interest rates and stuffs like that. Prosper or Prosper Marketplace Inc. is a San Francisco, California based company specializing in loans at low interest rates to the borrowers. In this dataset, we are using the data from the Posper to analyse it and trying to find the pattern in the Prosper data. This may be tedious because of the sheer size of the dataset and the complicated nature of all the financial datasets. I am using PYTHON(jupyter Notebook), an advanced high level programming language of the analysis with some of its most popular graphic package ggplot. The codes are visible in the HTML/PDF export for the benefit of both proffesionals in the field and laymen.**

**The dataset is comprised of 81 variables and contains 113937 entries. The variable that are explored in the dataset are the following Term :**

LoanStatus : Current status of the loan like chargedoff, completed, defauted etc…
Term : The length of the loan Expressed in months
BorrowerRate : The Borrower’s interest rate for this loan.
EmploymentStatus : Current type of employment
IsBorrowerHomeowner : Does the borrower owns house at the time of listing (True & False)
StatedMonthlyIncome : Monthly income of the borrower
MonthlyLoanPayment : Monthly loan payment amount
LoanOriginalAmount : Original amount of the loan
InvestmentFromFriendsAmount: Dollar amount of investment that were made by friends
LenderYield: The lender yield on loan, Lender yield is equal to the interest rate on loan less servicing fee
lp_netprincipalloss: The principal that remains uncollected after any recoveries

**Summary of the Findings**
After a rigorous and exceptional wrangling and analysis of the dataset, I discovered Majority of the loan is given to applicants with low monthly income and those with the employment status 'employed' and 'full-time' has higher priviledge to get huge amount of loan. I delved more and discovered Loan is mostly given to those who are home owners and home owners have the priviledge to get higher amount of loan. which makes me conclude that if you are a home owner and your employment status is the determinant of the loan original amount you get.
Lastly I explored losses and where majority of the losses came from, I discovered the higher amount of net principal loss came from home owner with employment status 'Not available'.
