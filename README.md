# Prosper Loan Dataset Exploration
## Analysed by [Opara-Eze Tochi](https://www.linkedin.com/in/oetochi/)


## Dataset Overview

> [Prosper](https://www.prosper.com/about) was founded in 2005 as the first peer-to-peer lending marketplace in the United States. Since then, Prosper has facilitated more than 22 billion USD in loans to more than 1,320,000 people.
Through Prosper, people can invest in each other in a way that is financially and socially rewarding.

> Over 110,000 peer-to-peer loans issued on the lending platform [Prosper](https://www.prosper.com/about) made up the dataset, which includes more than 80 different factors. My attention was primarily on how Monthly paycheck size of the borrower, the original amount of the loan requested, Employment status, and the kind of Occupation will affect the features of interest. To achieve this, I focused my attention on columns like Original Loan Amount, Borrower Annual Percentage Rate (BorrowerAPR) and BorrowerRate among others.


## Summary of Findings

> The distribution of BorrowerAPR and BorrowerRate is multimodal in nature

> From the histogram chart below, 4k, 10k and 15k are the most borrowed amounts in Prosper loan app

> Distribution of Stated Monthly Income of the borrowers is skewed to the right. This means that majority of Prosper client earn below 15k dollars per month

> The debt to income ratio seems a bit skewed to the right but we can as well conclude that it is normally distributed.

> Top 5 most popular occupation of the borrowers are Professional, Executive, Computer, Programmer, and Teacher

> I observed a negative correlation between Loan Original Amount and Borrower APR, that means as I earlier predicted higher loan amounts had lower borrower annual percentage return

> 50% of the current loan is below 10k dollars and the highest is within 35k dollars range; 75% of the loans that are defaulted fall within 5k - 10k dollars; 75% of the loans that are past due (16-30 days) are below 15k, and the highest defaulted loan amount is 15k

> Employment Status does not have enough data for Part-time, Retired, Self-employed and Not employed to show its interaction with ProsperRating (Alpha) and Most of the employed borrowers were C-rated followed by B and A respectively. Less than 5000 borrowers had the highest rating of AA-rating.

> Borrowers that have Employed, Self-employed and Others employment status borrow higher amount than part-time, retired,full time and not-employed borrowers.

> There is no clear positive correlation between stated monthly income and loan original amount requested

> There is a negative correlation between the LoanOriginAmount and BorrowerRate.
Obviously, as I had expected that interest rate should be lesser for higher loan amount, the trendline of the scatter plot shows that the negative correlation.

> 36 months term loans have higher BorrowerAPR than 12 or 60 months term.

> 75% of 12 months term loans have interest rate below 20%. This was a bit surprising for me. I had envisaged that shorter term loans should come with higher interest but obviously the data said something else. Longer term loans attracted higher interest. I assume the management of Prosper Loan App sdopted this strategy to encourage faster loan repayment.

> Generally, there is a negative correlation between LoanOriginalAmount and BorrowerRate for all 3 terms. Similar tren can be observed between LoanOriginalAmount and BorrowerAPR.

> The borrower APR and Loan Original Amount have a positive link. However, the relationship becomes negative as the rating drops from AA to HR. I believe that Prosper executives purposefully increased the APR for high-rated customers as the loan amount requested increased in order to maximise returns from the transaction (possibly because these customers have been with them for a long time and they are already loyal to the brand). In contrast, those with lower prosper ratings have lower APRs as the loan amount increases. I think this is being done on purpose to entice new clients—who most likely have low APRs—to try out the service.

> Similar conclusion can be drawn for this relationship between Loan Original Amount and Borrower Rate as in that of Loan Original Amount vs BorrowerAPR above.

> Highly rated borrowers (AA-B) have lower APR, though there is an incremental difference as the loan term increases from 12-60. But poorly rated borrowers attract higher APR.

> Highly rated borrowers (AA-B) have lower APR, though there is an incremental difference as the loan term increases from 12-60. But poorly rated borrowers attract higher APR.

> The BorrowerAPR increases from 12 - 36 months and then falls for 60months loan term for each employment status

> Borrowers with high monthly income and prosper rating tend to borrow loans of 12 months term duration.

## Key Insights for Presentation

> The borrower APR and Loan Original Amount have a positive link. However, the relationship becomes negative as the rating drops from AA to HR. Further exploration on the influence of loan term and prosper rating on the original loan amount shows that for better rating, the amount increases for all three terms.

> Unexpectedly, the borrower APR and loan amount have a negative link when the borrower's Prosper rating is between HR and B, but a positive correlation when the borrower's rating is between A and AA. Another intriguing finding is that for borrowers with HR-C rates, the APR decreases as the borrow time lengthens. However, the APR rises with the length of the loan for those with B-AA credit ratings.
