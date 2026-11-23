# grocery
grocery inventory dataset
## Description
This project described and evaluated the inventory of a grocery store. it was sourced from Kaggle.com. it comprises of 17 fields (columns) and 572 observations (rows). it consisted of 5 unanswered questions meant to give data insights for future decision making. 
## Data Cleaning
Data cleaning was done using power query. simple text transformation were done and irrelevant columns were removed.
## Procedure
This analysis was done using powerBI. Each question was answered using Data Analysis Expression(Dax).
Firstly, a data table was created from the date received field.
my date table =CALENDAR(MIN('Grocery_Inventory new v1'[Date_Received]),MAX('Grocery_Inventory new v1'[Date_Received])).
the table was then marked as a date table and merged on the data model view using 1-to-* relationship.
Dax table was created with various Dax measures added.
## Questions and Findings
1. What is the average stock quantity available per product category?
2. <img width="1019" height="586" alt="grocery1" src="https://github.com/user-attachments/assets/066879b6-3845-4c34-8aee-443a7407b971" />
 
3. Which suppliers contribute the most to total product inventory?
4. Which products have the longest shelf life before expiration, and how does that impact sales?
5. Which products are most likely to run out of stock based on last reorder levels? 
6. Can we predict seasonal demand for different product categories based on sales volume trends?
7. What are the optimal reorder levels for high-demand products to prevent stockouts? 

