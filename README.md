# Supermarket Sales Analysis

## Project Overview

This project analyzes supermarket sales data to identify patterns, trends, and key insights. The dataset contains information on sales transactions, including product categories, customer demographics, payment methods, and gross income. The goal of this analysis is to uncover sales trends, assess customer purchasing behavior, and provide actionable insights for business improvement.

## Dataset Details
- **Data:** Supermarket sales data
- **File Format:** Excel (.xlsx)
- **Key Columns:**
    - **Invoice ID:** Unique transaction identifier
    - **Branch:** Store branch (A, B, or C)
    - **City:** City where the store is located
    - **Customer Type:** Membership status (Member/Normal)
    - **Gender:** Customer gender
    - **Product Line:** Category of purchased product
    - **Unit Price:** Price per unit of product
    - **Quantity:** Number of items purchased
    - **Tax 5%:** Tax applied on the purchase
    - **Total:** Final amount paid (including tax)
    - **Date:** Date of transaction
    - **Time:** Time of transaction
    - **Payment:** Payment method (Cash, Credit Card, E-wallet)
    - **COGS:** Cost of goods sold
    - **Gross Income:** Profit from the transaction
    - **Rating:** Customer rating of their shopping experience

## Methodology
### 1. Data Cleaning and Preprocessing:
- Imported necessary libraries (pandas, matplotlib, warnings)
- Loaded the dataset and focused on specific columns
- Corrected inconsistencies and inaccuracies in the:
  - Customer Type column
  - Gender column (changed "M" and "Men" to "Male")
  - Product Line column (corrected spellings)
  - Unit column (filled missing values using a formula)
  - Total column (corrected missing values and applied a formula)
- Converted the Date column to datetime format
- Corrected spellings in the Payment column
- Replaced empty values in the Rating column with zero
### 2. Data Visualization:
- Used bar charts to answer the research questions

## Key Findings
1. *Most Profitable Branch*: Branch C was the most profitable.
2. *Customer Type with Highest Patronage*: Member type had the highest patronage, with 223 transactions.
3. *Most Patronized Product*: Home and Lifestyle product line was the most patronized, with 77 transactions.
4. *Product Line with Highest Sales*: Home and Lifestyle product line had the highest sales.
5. *Part of the Year with Highest Sales*: February had the highest sales.
6. *Most Used Payment Method*: E-wallet was the most used payment method, with 148 transactions.
7. *Payment Method with Highest Sales*: Credit Card brought in the highest sales.

## Technologies Used
- Programming Language: Python
- Libraries: Pandas, Matplotlib.

## Potential Improvements & Next Steps
- Additional Visualizations: Heatmaps for branch performance, deeper trend analysis.
- Statistical Testing: Hypothesis testing (e.g., t-tests, chi-square tests) to validate trends.
- Predictive Analysis: Implement machine learning models for sales forecasting.
- Customer Segmentation: Cluster analysis to group customers based on purchasing patterns.
- Time-Series Analysis: Examine seasonal trends in sales data.

How to Use
1. Clone this repository.
2. Open the Jupyter Notebook and download the data.
3. Run the cells to analyze the dataset and generate visualizations.

