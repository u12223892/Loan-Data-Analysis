# Prosper Loan Data Visualization Project
## by Brighton Zongondi

> A dataset containing 113 937 loans given to borrowers was provided by Udacity for the Data Visualization project, inorder to comply with the academic requiremnts of the ALX-T DATA Analytics nanodegree. Here we will explore the steps and processes that were taken to clean, explore and finally explain the findings discovered in this dataset.

## Dataset

> This dataset had 113 937 listed loans with 81 columns of variables ranging from Loan Original Amount, Occupation, Stated Monthly Income and Loan Term to name a few. Inorder to successfully conduct an Explanatory Data Analysis (EDA), the assessment and cleaning process is compressed into a concise chapter so that much more time is spend on the Exploratory and Explanatory Data Analysis of this project.

## Data Assessment and Cleaning

> 1. Look at the structure of the data
  2. Identify importatant or relevant variables for this project
  3. Remove duplicated rows
  4. Convert datatypes to the correct format eg Dates Datetime format
  5. Remove Loan listings without Prosper Ratings
  6. Fill in missing entries eg DebtToIncomeRatio
  7. Change datatype of listing category to string
  8. Save a new cleaned data set for the Exploration Analysis stage



## Summary of Findings

> Prosper Ratings follows a normal distribution, which informs us on the nature of rating index employed by the creditor. The most frequented rating is the Prosper Rating C.

>The majority of borrowers are Employed. This information will not assist in the investigation we seek, however it shows that Loans are preferrably given to Employed people who have a better chance in returning such loans.

>The biggest borrower is the unclassified group called Other, and the least borrower being the students according to the Borrower by Occupation barplot. However, Professionals exceed 10 000, and form the highest loan listings in the Prosper Loans Data.

>Loans given by the creditor are right skewed in the above StaetdMonthlyIncome distribution with peak Monthly income of about 6 000.00USD

>Across the 2009-2014 period, 2013 realised the most loans, while 2009 experienced the least loans being issued. It is important to note that 2009 was only a year after the Great Financial Crush caused by the housing market collapse of 2008 which triggered the what is dubbed at the 2008 financial crisis.

>There seem to be no points of interest in the day of the month distribution of loan listings. Therefore, no further investigation or probe will be conducted regarding this variate.

>The distribution of the DebtToIncomeRatio follows a near normal distribution with a center of 0.2. However, a further look at the value that towers above the frequency of 8000 might be an area to further investigate for anomalies.

>This distribution is near Multimodal at a Borrower APR of 1.80 and 2.10, with an unusual surge above 7000 at a Borrower APR of 0.36 which will be regarded as an outlier.

>It seems the least occurrances are at the highest Loan Original Amounts exceeding $20 000.00. The obvious expactation is that more people take the least easily payable loans, or they qualify for smaller loans. This should be looked at incontrast to Monthly Income and Ratings to see if there is a relationship.

>Monthly payments are right skewed peaking at above 35 000, which is an expected distribution as more people are probably inclined to minimise thier monthly loan payments so they are left left with more money to spent. This istribustion will be looked at against Monthly Income and Loan Amount for further insights.

>Trends to take note of are the Loan Original Amount and Borrower APR as the change across the grid (Term, Prosper Rating, and Employment Status). It is noteworthy that as Loan Original Amount increases, the loan Term increases, as well as when the Prosper Rating gets to a higher rating of AA. Borrowers with a form of income are able to borrow more loans, however there is more unknown information in the Other category of Employment status that is showing significant data entries.

>The relationship has a negative correlation. In the above plot, lower loan amounts have a higher Borrower APR, and this changes across the graph as Loan Original Amount increases. This is expected, as not many loans are taken (Borrower APR) at high Loan Amounts.

>Borrower APR has a negative correlation with Loan Original Amount as shown in the plot about above. Borrower APR is a measure of how an individual borrows a certain loan original amount in a year. The results do make sense as Borrower APR dips at high Loan Original Amounts. This due to high loan amount being a deter in terms of paying back, or not being granted as borrowers may not qualify for such loan amounts.


## Key Insights for Presentation

> The months ranging from October through to January have amongst the highest Loan listings. This is expected as during that period it is a festive holiday, and the household spending is normally high during this time period.

> At lower Loan Original Amounts, Borrower APR has a bigger range,  but this decreases as the Loan Original Amount increases. Thus in gerenral Borrower APR decreases with Loan Original Amount.

> DebtToIncomeRatio distribution has two multimodal peaks at 0.2 and another at 0.25 thereby indicating that most people prefer a DebtToIncomeRatio of about 1:4.

>Across Prosper Rating HR to B, Loan Original Amount is negatively correlated to Borrower APR, but this correlation flips over to a positive correlation at Prosper Ratings of AA and A.





















