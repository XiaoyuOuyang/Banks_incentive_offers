# Banks_incentive_offers
This project aims to understand what factors drive banks to use dollar incentive offers (e.g., a $200 bonus for depositing $3,000) to attract deposits. Two examples are given in the links below: 
https://www.bankrate.com/banking/best-bank-account-bonuses/#checking-citibank
https://www.bankrate.com/banking/best-bank-account-bonuses/#checking-bmo

# Datasets:
The data is unavailable but is described in detail below.
A.	A dataset including banks’ promotional offers, named “DatasetA.csv”
We have three identifiers in the dataset, Primary Company (which is often a bank), Campaign ID, and Observation ID. For each Primary Company, there might be multiple Campaigns in a month. Within each Campaign, there could be multiple incentives. For example:
Primary Company     Campaign ID       	          Incentive Text    	Observation ID
Bank A                    	Campaign a              	Incentive 1               	1
Bank A                    	Campaign a              	Incentive 2               	2
Bank A                    	Campaign b              	Incentive 3               	3
B.	A dataset including banks’ quarterly financial variables, named “DatasetB.csv”. You do not need to make use of all the variables.

# Tasks:
1. 	There is a field in dataset A called “Incentive”. We need to extract several variables that describe the incentive. One variable we need is the dollar amount of the bonus. Another variable that may be useful is the required deposit amount. Feel free to construct other variables that you think are useful for the analysis.
2.     Please match datasets A and B based on banks’ names. Note that the datasets are from two different sources, so the names do not perfectly line up between the two. Please describe your matching results in the paper.
3. 	Explore what factors drive banks to use incentive offers and write a short paper, explaining your findings. Feel free to add other datasets (e.g., macroeconomic variables, such as the Fed funds rate) that you think can be useful. If you produce any tables/figures, please define the variables that you use.

