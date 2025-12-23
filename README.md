# ecommerce-business-transaction-analysis
Focused EDA of e-commerce transactions analyzing Price and Quantity to understand purchasing patterns. Cleaned data, visualized distributions, and handled outliers for clear insights.

-----------------------------------------------------

# E-commerce Transactions: Price & Quantity Analysis

## Overview
Focused exploratory data analysis (EDA) of e-commerce transactions, analyzing **Price** and **Quantity** to understand purchasing patterns.

## Dataset
- `Sales Transaction v.4a.csv`
- Key columns: TransactionNo, Date, ProductNo, ProductName, Price, Quantity, CustomerNo, Country

## Tools
- Python, Pandas, Matplotlib, Seaborn

## Analysis Highlights
- Removed invalid transactions (Price ≤ 0 or Quantity ≤ 0)
- Filled missing CustomerNo with "Guest"
- Created `TotalAmount = Price * Quantity`
- Visualized Price and Quantity distributions (capped extremes and log-scale for skewed data)

## Key Insights
- Most products are low-priced
- Most orders have small quantities
- Extreme values are rare and handled for visualization clarity
