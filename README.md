# (Prosper Loan Data Exploration)
## by (Sandra Nwankwo)


## Dataset

> Loan Data from Prosper is a financial dataset related to the loan, borrowers, lenders, interest rates, and stuff like that. It contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. Prosper is a San Francisco, California-based company specializing in loans at low-interest rates to borrowers. The company became the first firm to enter the peer-to-peer lending arena when it launched in 2005. In this dataset, we are using the data from Prosper to analyze it and try to find the pattern in the Prosper data.

## Summary of Findings

> The primary objective of my investigation was to know the leading motivations of borrowers when applying for loans and the factors that favor loan eligibility

>While exploring this dataset, I found some interesting and surprising insights. Surprisingly to me, the leading motivation for loan collection was debt consolidation. This means that majority of the borrowers collected loans to settle their debt, therefore, incurring more debt in the process. Another insight from this exploration was that more people collected loans for boat acquisition than for home improvement. In fact, the leading motivations were debt consolidation, Baby & Adoption, boat (acquisition, cruise, or maintenance - it is not exactly clear), business, wedding, engagement ring, and large purchases). The least motivation for loan collection was student use. Based on the other variable relationships and interactions explored in this investigation, I assume that one of the reasons stated below explains why Student use was the least in the Listing Category:

>* The company is hesitant to give out loans to students because of their earning capacity and employment status

>* Students are not comfortable requesting academic loans from this company

>As I explored the relationship between the variables relevant to my investigation, I made more interesting observations. I found a negative correlation between Borrower APR, loan original amount, loan term, and prosper rating. This means that the larger the loan, the longer the loan terms. This will most likely encourage borrowers to request more loans. From the interaction between Loan status, employment status, income range, and borrowers' APR, we can see that employed people, full-time workers, and higher-income earners have higher loan eligibility and lower borrower APR. 

>We can also conclude that having collateral and a higher wage help get a higher loan amount. It is clearly visible that being a homeowner is a very important element to get a higher loan amount. Another point is the difference in the interest rate applied depending on the conditions. In other words, Prosper ratings (excluding E ratings (3-year loans and his 5-year loans have the same interest rate) and HR ratings). This is because a longer duration increases the risk of this operation with rising interest rates.

## Key Insights for Presentation

> My main interest in this dataset investigation was to understand the different motivations of borrowers when applying for loans. I also want to know the conditions that favor loan eligibility. Not all the variables in this dataset were necessary for this investigation, hence my focus was on the key features relevant to this dataset exploration. I used scatter plots, histograms, and boxplots to create detailed visualization for better insights and observation. These are some of the key insights from my dataset exploration

> Employed people, full-time workers, and higher-income earners have higher loan eligibility and lower borrower APR.
> The leading motivation for loan collection was debt consolidation
> Larger loans have lower borrowers APR
> Employed and Full-time have the lowest APR despite the category of loan status, while the non-employed have the highest APR.
> Higher income earners can enjoy larger loans at a lower borrower APR