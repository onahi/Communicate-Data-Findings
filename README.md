# Exploration of Prosper Loan Dataset 
## by Paul Ajogi


## Dataset

The data set contains 113,937 loans with 81 variables on each loan, including 
loan amount, borrower rate (or interest rate), current loan status, borrower 
income, and many others.

The dataset can be found [here] ( https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv ).
The data dictionary available [here] ( https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0 ) 
explains the variables in the data set.


## Summary of Findings

I discovered that, the BorrowerRate had more impact on the status of the loans 
borrowed from Prosper Loans. It was discovered that the Loan status categories 
with a more positive outcome like the completed and FinalPaymentInProgress had 
lesser median value than those with negative outcome like Defaulted and Past Due
that had higher median values. This was an indication that  higher borrower rate
were more concentrated  in categories that indicates negative outcomes than those
of positive outcomes.

Aside the main variable of interest `LoanStatus`, I also explored how the other
variables of interest relates to the `BorrowerRate`. I noticed that the `BorrowerRate` 
and the `BorrowerAPR` are positively corrolated.


## Key Insights for Presentation

For the presentation, I focused on how the Borrower's Rate influence the 
Loan Status and how the Borrower's Rate relates with the Borrower's APR. I started
by intruducing the Loan Status and the count for each category of Loan Status. I
then checked the distribution of the Borrower's Rate before plotting to see 
their relationship.

After introducing the variables of interest, I then used the violin plot the
check the relationship between the Loan Status and Borrowers Rate to see how they
influence each other. I then used a scatter plot to see how the Borrowers Rate and
Borrowers APR relates in all categories of Loan Status.