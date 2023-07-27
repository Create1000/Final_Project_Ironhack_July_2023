# Final_Project_Ironhack_July_2023

### Customer Personality Analysis
#### Goal
The goal of the project is to analyse the customers in order to make better strategic decisions regarding product type, marketing campaigns. We want to get a picture of who is our "best" or "most profitable" customer. 
The following questions should be answered:
1. Who are the existing and potential customers?
2. Which customers are "valuable"?
3. Which products do the existing and potential customers like?

##### We have the following values:
***
##### People

<li>•	ID: Customer's unique identifier
•	Year_Birth: Customer's birth year
•	Education: Customer's education level
•	Marital_Status: Customer's marital status
•	Income: Customer's yearly household income
•	Kidhome: Number of children in customer's household
•	Teenhome: Number of teenagers in customer's household
•	Dt_Customer: Date of customer's enrollment with the company
•	Recency: Number of days since customer's last purchase
•	Complain: 1 if the customer complained in the last 2 years, 0 otherwise
Products
•	MntWines: Amount spent on wine in last 2 years
•	MntFruits: Amount spent on fruits in last 2 years
•	MntMeatProducts: Amount spent on meat in last 2 years
•	MntFishProducts: Amount spent on fish in last 2 years
•	MntSweetProducts: Amount spent on sweets in last 2 years
•	MntGoldProds: Amount spent on gold in last 2 years
Promotion
•	NumDealsPurchases: Number of purchases made with a discount
•	AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
•	AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
•	AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
•	AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
•	AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
•	Response: 1 if customer accepted the offer in the last campaign, 0 otherwise
Place
•	NumWebPurchases: Number of purchases made through the company’s website
•	NumCatalogPurchases: Number of purchases made using a catalogue
•	NumStorePurchases: Number of purchases made directly in stores
•	NumWebVisitsMonth: Number of visits to company’s website in the last month
Analysis Approach
Data Cleaning
•	I checked the information about our columns and data type.
•	Null values check and delete in my case (Income: 24 values)
•	Delete the both columns 'Z_Revenue', 'Z_CostContact', because they have equal values and are irrelevant for the analysis.
•	Duplicates check
•	Remove two values Absurd and YOLO in ‘Marital_Status’.
•	Transform ‘Dt_Customer’ to datetime and create the new column ‘Yaer’ and “Age” for customers age. 
Exploratory Data Analysis
•	Statistics Summary
•	Numerical data analysis
•	Categorical data analysis
•	EDA for the different relationships between different variables
•	Features correlation (matrix)
Tableau
Link to the tableau you can find here
Dataset Used
Customer Personality Analysis
https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis
Tools and Technologies used
Python: for Data Cleaning, for Exploratory Data Analysis
Tableau: for Visualization


