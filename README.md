Welcome to the UMass Dartmouth Big Data Club submission to the Brown Datathon Competition 2020! This repository contains the code we used to clean the data and train models, allowing our analysis to be reproduced.

For this challenge, we trained a graph neural network on data from three sources. The first source came from Citizens Bank, and was provided at the start of the Brown Datathon. Next, we obtained a variety of employment, income, housing, and commuting data from the US Census Bureau ACS 5-year estimates (Tables DP03 and DP04). Finally, we obtained a number of variables related to home price and sales data from Zillow Research, being careful not to use data from after the specified prediction time frame of April to September. 

Sources: 

US Census Bureau ACS 5-year estimates, 2018, All ZIP codes
Table DP03: https://data.census.gov/cedsci/table?q=dp03&hidePreview=false&tid=ACSDP5Y2018.DP03
Table DP04: https://data.census.gov/cedsci/table?q=dp04&tid=ACSDP1Y2018.DP04

Zillow Research - https://www.zillow.com/research/data/
Includes the following:
Median Sale Price (Raw)
Median Price Cut (%)
Foreclosure Resales (%)
Monthly For-Sale Inventory (Raw)
New Monthly For-Sale Inventory (Raw)
Median Daily For-Sale Inventory (Raw)
