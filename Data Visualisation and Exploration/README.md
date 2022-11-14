# (Dataset Exploration Title)
## by (Adekemi Kadri)


## Dataset

> The Prosper Loan dataset consist of 113937 entries with 81 columns.


## Summary of Findings

- According to the results of the univariate analysis, the majority of borrowers have credit scores between 4 and 8, with a few outliers in the credit score column. Those who are employed hold loans at a higher rate than those who work part-time, are unemployed, or are retired. In comparison to the rest, those with incomes between $25K and $74,9K applied for the most loans, while those with no income or no job submitted the fewest applications.Because of the skewness seen in the results of using conventional plots, log scale transformation was applied to the majority of the columns.

- When using bivariate analysis, it was anticipated that there would be a negative connection between borrower rate and credit score since, in the event of delinquencies, the borrower rate would be larger the lower the credit score. LoanCurrentDaysDelinquent vs. CreditScore and LoanCurrentDaysDelinquent vs. BorrowerRate, however, do not significantly correlate. It demonstrates how having a high Prosper Score correlates with a lower Borrower Rate and a higher Credit Score. It is not surprising that those with 0 or no income displayed have the most days past due because they are unlikely to pay the interest due to having no income. However, people with no income have the best credit scores compared to the others, which is intriguing and necessitates more study. The most days past due belong to those whose employment status is unclear, and they may also be connected to people whose income is not reported. Additionally, they are the group with the lowest average credit score. After considerable investigation, it appears that the majority of borrowers who claim to have no income are most likely mistaken because they are working, which makes it improbable that they are getting paid nothing or on a commission basis. The expected negative correlation between credit score and borrower rate was found to be coff of 0.489.

- The multivariate plot seen above while performing multivariate exploration displays a number of indicators.Given that each prosper score ranges from 600 to 900, it would appear that having a high credit score does not automatically result in a higher prosper score.
Regardless of the borrower's work situation, we can observe that the borrower's rate is lower the higher their credit score is.

- Borrower APR and loan original amount were found to be negatively correlated, meaning that the larger the loan amount, the lower the APR.
BorrowerAPR and BorrowerRate are highly correlated.

- The loan amount increases as the credit rating improves, while the borrower APR decreases.

- The APR for AA-B ratings rises as the loan term lengthens. For C to HR ratings, the APR decreases as the loan term lengthens.
- Borrowers will pay more interest on their loans if the APR is high.

- The highest median Borrower rate is found in the income range of $1-24,999k. It deviates from the trend of median borrower rates decreasing with increased income in income ranges of $25k and above.

- The original loan amount is positively related to the stated monthly income, which makes sense because borrowers with higher monthly income can take out more loans. The loan amount increases as the loan term lengthens. 
- Unemployed people have the highest median borrower rate. Unemployed people pay higher interest rates on loans.

## Key Insights for Presentation

>21 variables were chosen and investigated out of the 81 columns present in the data. The relationship between credit score and borrower rate was inverse. A solid credit score combined with a low borrower rate did not, however, reduce the number of delinquent days, which was an interesting finding.
