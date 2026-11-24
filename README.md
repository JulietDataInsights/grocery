# Grocery - Power BI
Grocery inventory dataset
## Table of Content
- [Indrodution](#introduction)
- [Project Objective](#project-objectives)
- [Description of Dataset](#description-of-dataset)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [KPIs](#kpis)
- [Research Questions](#research-questions)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)

## Introduction
This project described and evaluated the inventory of a grocery store.

## Project Objectives
  This project is intended to provide insight into the inventory of a grocery store, as a means to influences future
  decision-making

## Description
It was sourced from Kaggle.com. it comprises of 17 fields (columns) and 572 observations (rows). it consisted of 5 unanswered questions meant to give data insights for future decision making. 

## Data Cleaning
Data cleaning was done using power query. simple text transformation were done and irrelevant columns were removed.

## KPIs
Average Sales Volume
Total Number of Suppliers
Max Date Recieved
Total Stock Quantity
Total Sales Volume 

## Research Questions
1. What is the average stock quantity available per product category? 
2. Which suppliers contribute the most to total product inventory?
3. Which products have the longest shelf life before expiration, and how does that impact sales?
4. Which products are most likely to run out of stock based on last reorder levels? 
5. Can we predict seasonal demand for different product categories based on sales volume trends?
6. What are the optimal reorder levels for high-demand products to prevent stockouts? 


1. What is the average stock quantity available per product category?
   The average quantity was measured using
   Avg Stock Qty = AVERAGE('Grocery_Inventory new v1'[Stock_Quantity])
<img width="1019" height="586" alt="grocery1" src="https://github.com/user-attachments/assets/066879b6-3845-4c34-8aee-443a7407b971" />
Seafood has the highest average stock quantity, while grains had the lowest average stock quantity. since, grain are mainly consumened, it is recommended that subsequant suplies should be focused mainly on grains
 
2. Which suppliers contribute the most to total product inventory?
   <img width="1020" height="573" alt="grocery3" src="https://github.com/user-attachments/assets/1b6d9ae5-410f-4247-9eec-09812dd2059f" />
    Katz, twitterwire, meevee, quartz and feedfire are our most prominent suppliers.
  
3. Which products have the longest shelf life before expiration, and how does that impact sales?
   <img width="1017" height="575" alt="grocery2" src="https://github.com/user-attachments/assets/8eba218e-c13b-4e4c-9e25-d3dbf0ae8267" />
    There will be reduction in sales volume, because the product are mostly expired. hence sell off the expired product to local farms for feed or discard then.
They should place a re-order and ensure they check expiration date before making purchase. 

4. Which products are most likely to run out of stock based on last reorder levels?
   <img width="398" height="335" alt="grocery2 - Copy" src="https://github.com/user-attachments/assets/6cf60874-09fd-461d-a19a-ca3c016bfede" />
    There is 30% increase in the optimal re-order level which are favourable to some of the products that has high demand status while some of the high demand status product need additional increase  or should be look into since there optimal re-order level is higher than the sales volume. 
 
5. Can we predict seasonal demand for different product categories based on sales volume trends?
   <img width="385" height="187" alt="grocery2 - Copy (2)" src="https://github.com/user-attachments/assets/00e4d7db-03b1-4137-8aa0-3b150eaf9208" />

6. What are the optimal reorder levels for high-demand products to prevent stockouts?
    Re-order for high demand should be improved by 50%

