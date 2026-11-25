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

## Key Findings
1. The average stock quantity ranges from 50.86 to 62.23 (Grains & Pulses - Seafood).
Avg Stock Qty = AVERAGE('Grocery_Inventory new v1'[Stock_Quantity])
<img width="218" height="102" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/b8865cef-d24f-4320-9fbe-671130bc0a75" />

3. Katz, Twitterwire, Meevee, Quatz and Feedfire contributed the most to the product inventory.
<img width="385" height="385" alt="grocery3" src="https://github.com/user-attachments/assets/015a5c4a-f479-4231-ba08-9afd17a3534c" />

4. The products with the longest shelf-life are Garlic, Banana, Rice Flour.
<img width="391" height="326" alt="grocery2" src="https://github.com/user-attachments/assets/330a76fe-6151-4118-a130-677bf7828ba3" />

5. The following products are most likely to run out of stock based on last reorder level.
   Rice flour, coconut,raw sugar, evaporated milk amongst others.
<img width="398" height="335" alt="grocery2 - Copy" src="https://github.com/user-attachments/assets/c157ba1a-bd45-4915-98d0-a114bcb8d53a" />

6. The seasonal demand for different product categories is expected to be between 528 and -259. This indicates that a drop in demand would reduce sales by 259.
<img width="385" height="187" alt="grocery2 - Copy (2)" src="https://github.com/user-attachments/assets/38572cf5-7260-4c43-841a-3fdfd6d3cc36" />

7. The optimal reorder level is 50% of the current reorder level.


## Recommendation
- Reorder quantity should be increased by 50% of the current reorder level.

  ## Conclusion
  The management should consider an increase in the reorder level in other to avoid stock out and apply first in first out(FIFO) method to reduce the amount of expired product in the store.


