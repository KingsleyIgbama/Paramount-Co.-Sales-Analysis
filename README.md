# Paramount Co. Sales Analysis

## Introduction
This repository contains an in-depth analysis of sales trends, profitability, and customer segmentation for Paramount Co. using historical sales data. The objective is to identify key performance metrics, understand seasonal variations, and provide recommendations to improve revenue and operational efficiency.

## Data Overview
- **Source**: Kaggle.com (E-commerce transactions dataset)
- **Contents**: Customer purchases, shipping details, profitability metrics
- **Industry**: Retail & E-commerce
- **Stakeholders**: Sales Managers, Marketing Team, Supply Chain Managers, Finance Team, Executives & Business Owners

### Data Structure
#### Independent Variables:
- Order Date, Ship Date, Ship Mode, Customer ID, Segment, Region, Product ID, Category, Sub-Category

#### Dependent Variables:
- Sales, Profit, Discount, Quantity

## Data Processing
### Data Cleaning
- Removed duplicate records and corrected inconsistent values
- Standardized product categories and pricing data
- Converted date formats for accurate time-series analysis

### Handling Missing Values
- Interpolated missing sales data points using average sales trends

## Key Insights
### Sales Trends
- Peak sales months: **March, September, and November** (holiday & promotional impacts)
- **West and East** regions generate the highest revenue, while the **South** underperforms
- **Technology** is the highest-grossing category, followed by **Furniture** and **Office Supplies**

### Correlations
- Higher discounts reduce profit margins, especially in **Furniture**
- Faster shipping correlates with higher order values

### Regional Performance
- **West & East**: Over 60% of total sales
- **South**: Needs targeted marketing efforts

### Customer Segmentation
- **Consumer** segment has the highest sales (~$1.16M), followed by **Corporate** and **Home Office**
- **Corporate** customers have higher average order values

### Shipping Mode Analysis
- **Standard Class**: 59% of sales (cost-conscious customers)
- **First Class & Same-Day**: Higher revenue per order (potential for premium shipping promotions)

## Recommendations
### Business Growth
- Increase marketing efforts in Q1 and Q3 to leverage peak months
- Expand sales in underperforming regions (South) with localized promotions

### Profitability Improvement
- Re-evaluate discounting strategies, especially for Furniture
- Encourage premium shipping adoption by bundling faster delivery with high-ticket purchases

### Customer Retention
- Implement loyalty programs for repeat buyers
- Offer personalized promotions for **Corporate** clients to maximize high-value transactions

## Conclusion
This analysis provides actionable insights to optimize pricing, improve customer retention, and expand regional presence. By leveraging these findings, Paramount Co. can drive sustainable growth and enhance profitability.

---
### Repository Contents
- `Technical_Report.pdf` - Original report
- `Data_Cleaning.ipynb` - Jupyter Notebook for data pre-processing
- `Sales_Analysis.ipynb` - Notebook with trend analysis and visualization
- `Recommendations.pdf` - Summary of key findings and strategic actions

**Author:** Kingsley Igbama

