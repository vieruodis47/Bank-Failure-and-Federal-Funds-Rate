# Bank-Failure-and-Federal-Funds-Rate

In this project, we wish to explore the relationship between federal funds rate and commercial bank failures in the United
States from 2000 to 2006. We know that the federal fund rate has crucial impacts on bank operations as it directly changes
the cost of short-term borrowing between banks and therefore affects the prime rate that banks charge customers. Banks,
though generally resilient to periodic fluctuations in the economy, are not immune to black swan events and severe
recessions.

Our questions of interests mainly involve around the following two topics:
1. How do Federal Reserve interest rate hiking cycles transmit to commercial bank failures over time?
2. What is the average duration of the lag between monetary tightening peaks and waves of FDIC receiverships?
Analysis

We use two publicly available datasets: the FDIC Failed Bank List, which records bank closing dates, locations, and
acquiring institutions, and the Federal Reserve Bank of St. Louis's FRED dataset, which provides monthly effective
federal funds rates (FEDFUNDS).

To address these questions, we plan to adopt a two-dimensional approach. First, along the time dimension, we group the
bank failure data by year and date and compare against federal funds data to identify peak failure period and measure the
delay it takes for rate hikes to actually hit banks. Second, along the geographical dimension, we group the bank failure
data by state to show where bank failures are the most concentrated.
