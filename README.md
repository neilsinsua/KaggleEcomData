# Kaggle E-Commerce Project

## Project Overview

Analysing e-commerce transactional data to:

- Insights into sales trends based on time
- Understand customer behaviour
- Creating an interactive dashboard for stakeholders

## Data Source

This is a transnational dataset from Kaggle which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## Data Structure

![datastructure](datastructure.png)

| InvoiceNo | StockCode | Description                        | Quantity | InvoiceDate         | UnitPrice | CustomerID | Country        | InvoiceYear | InvoiceMonth | InvoiceDay | InvoiceTime | GrandTotal |
| --------- | --------- | ---------------------------------- | -------- | ------------------- | --------- | ---------- | -------------- | ----------- | ------------ | ---------- | ----------- | ---------- |
| 536365    | 85123A    | WHITE HANGING HEART T-LIGHT HOLDER | 6        | 2010-12-01 08:26:00 | 2.55      | 17850      | United Kingdom | 2010        | 12           | 1          | 08:26:00    | 15.30      |
| 536365    | 71053     | WHITE METAL LANTERN                | 6        | 2010-12-01 08:26:00 | 3.39      | 17850      | United Kingdom | 2010        | 12           | 1          | 08:26:00    | 20.34      |

## Insights Summary

### Sales Performance

- **Overall Sales Trends:** What are the daily, weekly, monthly, and annual sales trends?
- **Seasonal Patterns:** Are there seasonal patterns in sales?

### Product Insights

- **Best/Worst Selling Products:** Which products are the top and bottom performers based on `Quantity` sold and `GrandTotal` revenue?
- **Co-Purchased Items:** What products are frequently purchased together (i.e., appear on the same `InvoiceNo`)?

### Customer Behavior

- **RFM Segmentation:** How can customers (`CustomerID`) be segmented based on:
  - **Recency:** Their last `InvoiceDate`?
  - **Frequency:** The total number of `InvoiceNo`s?
  - **Monetary Value:** Their total `GrandTotal` spend?
- **Top Customers:** Who are the customers (`CustomerID`) with the highest total `GrandTotal` spend?
- **Repeat Purchase Analysis:** What is the frequency of purchases for individual `CustomerID`s over time (using `InvoiceDate`)?
- **Geographic Sales:** Which `Country` generates the most sales revenue (`GrandTotal`)?

## Recommendations

## Dashboard

[Interactive Dashboard](https://public.tableau.com/views/KaggleEcomm/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
