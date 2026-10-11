# Prosper Loan Data Exploration

## Dataset

The data consists of 113,937 Prosper loans with 81 variables, including
information about loan characteristics, borrower financial attributes, credit
profiles, interest rates, and loan status. The dataset was provided as part of
Udacity's Data Visualization project and is based on Prosper's loan data.

## Summary of Findings

In the exploration, I found that borrower interest rates are concentrated
mainly between 8% and 30%, with several noticeable peaks in the distribution.
There is also a moderate negative relationship between the original loan
amount and borrower interest rate, with larger loans generally associated with
lower interest rates. Smaller loans show a much wider range of interest rates,
including many of the highest rates in the dataset.

Loan term also has an association with borrower interest rates. The 60-month
loans have a slightly higher median interest rate, while 36-month loans show
the greatest variability and contain several high-rate outliers. The
relationship between loan amount and interest rate remains visible across
different loan terms.

Outside the main variables of interest, I found that loan amount and loan term
have a moderate positive relationship, while loan term and borrower interest
rate have almost no linear correlation when considered independently.

## Key Insights for Presentation

For the presentation, I focus on three key relationships discovered during
the exploratory analysis. I first introduce the overall distribution of
borrower interest rates to establish the typical range of borrowing costs.

Next, I examine the relationship between original loan amount and borrower
interest rate, which shows that larger loans generally tend to have lower
interest rates.

Finally, I compare borrower interest rates across the three available loan
terms. This shows differences in both the typical interest rate and the
variability of rates across 12-, 36-, and 60-month loans.