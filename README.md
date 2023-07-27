# Final_Project_Ironhack_July_2023

### Customer Personality Analysis

#### Goal
The goal of the project is to analyse the customers in order to make better strategic decisions regarding product type, marketing campaigns. We want to get a picture of who is our "best" or "most profitable" customer. 
The following questions should be answered:
1. Who are the existing and potential customers?
2. Which customers are "valuable"?
3. Which products do the existing and potential customers like?
***
##### We have the following values:

##### People
<li> ID: Customer's unique identifier
<li> Year_Birth: Customer's birth year
<li> Education: Customer's education level
<li> Marital_Status: Customer's marital status
<li> Income: Customer's yearly household income
<li> Kidhome: Number of children in customer's household
<li> Teenhome: Number of teenagers in customer's household
<li> Dt_Customer: Date of customer's enrollment with the company
<li> Recency: Number of days since customer's last purchase
<li> Complain: 1 if the customer complained in the last 2 years, 0 otherwise
  
##### Products
<li> MntWines: Amount spent on wine in last 2 years
<li> MntFruits: Amount spent on fruits in last 2 years
<li> MntMeatProducts: Amount spent on meat in last 2 years
<li> MntFishProducts: Amount spent on fish in last 2 years
<li> MntSweetProducts: Amount spent on sweets in last 2 years
<li> MntGoldProds: Amount spent on gold in last 2 years
  
##### Promotion
<li> NumDealsPurchases: Number of purchases made with a discount
<li> AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
<li> AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
<li> AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
<li> AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
<li> AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
<li> Response: 1 if customer accepted the offer in the last campaign, 0 otherwise
  
##### Place
<li> NumWebPurchases: Number of purchases made through the company’s website
<li> NumCatalogPurchases: Number of purchases made using a catalogue
<li> NumStorePurchases: Number of purchases made directly in stores
<li> NumWebVisitsMonth: Number of visits to company’s website in the last month
  
#### Analysis Approach

##### Data Cleaning

1. I checked the information about our columns and data type.
<li> 2. Null values check and delete in my case (Income: 24 values)
<li> 3. Delete the both columns 'Z_Revenue', 'Z_CostContact', because they have equal values and are irrelevant for the analysis.
<li> 4. Duplicates check
<li> 5. Remove two values Absurd and YOLO in ‘Marital_Status’.
<li> 6. Transform ‘Dt_Customer’ to datetime and create the new column ‘Yaer’ and “Age” for customers age. 
  
##### Exploratory Data Analysis
<li> 1. Statistics Summary
<li> 2. Numerical data analysis
<li> 3. Categorical data analysis
<li> 4. EDA for the different relationships between different variables
<li> 5. Features correlation (matrix)

#### Tableau

Link to the tableau you can find here

#### Dataset Used
Customer Personality Analysis:
https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis

#### Tools and Technologies used
Python: for Data Cleaning, for Exploratory Data Analysis

Tableau: for Visualization


