# Banking Domain Analysis

## Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) on a banking dataset to uncover customer behavior patterns, transaction dynamics, and operational trends. The objective is to derive actionable insights that can support data-driven decision-making, customer segmentation, and service optimization in the banking sector.

In addition to the EDA performed using Python, a Power BI dashboard was developed to present key metrics and trends through interactive visualizations.

## Objectives

- Analyze customer demographics and behavior across various services.
- Investigate transaction patterns by amount, type, and frequency.
- Examine branch-level performance and service usage trends.
- Support strategic recommendations for improving customer satisfaction and operational efficiency.

## Dataset Description

The dataset (`Banking.csv`) contains customer and transactional data for a banking institution. It includes the following fields:

| Column Name           | Description                                          |
|------------------------|------------------------------------------------------|
| Customer_ID            | Unique identifier for each customer                  |
| Age                   | Age of the customer                                  |
| Gender                | Gender of the customer                               |
| Job                   | Occupation of the customer                           |
| Marital_Status        | Marital status of the customer                       |
| Account_Type          | Type of account held                                 |
| Balance               | Current balance in the account                       |
| Transaction_Type      | Type of transaction performed                        |
| Transaction_Amount    | Amount involved in the transaction                   |
| Transaction_Date      | Date of transaction                                  |
| Branch                | Branch at which the transaction occurred             |
| Credit_Score          | Customer’s credit score                              |

*Note: Column names and formats were cleaned and standardized during preprocessing.*

## Analytical Focus Areas

### Customer Analysis

- Gender and age distribution
- Customer segmentation by job and marital status
- Account type usage patterns

### Transaction Analysis

- Transaction frequency by day and month
- Most common transaction types
- High-value transactions by account type and customer demographic
- Transaction distribution across branches

### Branch-Level Analysis

- Volume and value of transactions by branch
- Branch-wise customer base characteristics
- Comparison of average balances and credit scores

### Financial Insight Generation

- Correlation between credit score and transaction behavior
- Identification of high-value customers
- Monthly and seasonal transaction trends

## Methodology

1. **Data Cleaning and Preprocessing**
   - Checked for nulls, duplicates, and inconsistent formatting.
   - Parsed date fields and standardized data types.

2. **Feature Engineering**
   - Extracted day, month, and weekday from transaction dates.
   - Grouped customers by age brackets.
   - Derived transaction categories (e.g., high-value, low-value) based on thresholds.

3. **Exploratory Data Analysis**
   - Used pandas and seaborn for trend identification and segmentation.
   - Generated visual summaries and correlation matrices.

4. **Dashboard Development**
   - Built a Power BI dashboard to summarize insights for stakeholders.
   - Visuals include bar charts, KPIs, line charts, and filters by branch, transaction type, and account type.

## Power BI Dashboard

The Power BI dashboard provides:

- Branch-wise transaction volume and average transaction value
- Customer demographic breakdown (gender, age group, occupation)
- Time-series analysis of transaction behavior
- Credit score segmentation by account type and branch

The dashboard supports interactive filtering and drill-down capabilities for in-depth analysis.

## Tools and Technologies

- **Python (Jupyter Notebook)** – Data cleaning, transformation, and EDA
- **Pandas, NumPy** – Data manipulation and aggregation
- **Matplotlib, Seaborn** – Data visualization
- **Power BI** – Dashboard development and stakeholder presentation

## Files Included

- `BankEDA (Version 1).ipynb` – Jupyter Notebook containing the full analysis
- `Banking.csv` – Cleaned banking dataset used for analysis
- `Banking Dashboard.pbix` – Power BI file for interactive reporting and visualization

## Conclusion

The analysis highlights key trends in customer behavior, transaction activity, and branch performance. Insights from the project can inform:

- Strategic targeting of customer segments
- Optimization of service offerings
- Improvements in customer experience
- Branch-level operational enhancements

This project demonstrates how exploratory data analysis and business intelligence tools can be leveraged to generate meaningful insights in the banking domain.
