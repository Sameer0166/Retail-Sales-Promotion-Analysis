# Retail Sales & Promotion Analysis Dashboard

## Project Overview

The **Retail Sales & Promotion Analysis Dashboard** is a Power BI project developed to analyze retail sales performance, customer purchasing behavior, product profitability, and promotional effectiveness. The project utilizes a **Star Schema** data model to organize transactional and dimensional data, enabling efficient reporting and business analysis.

The dashboard provides decision-makers with insights into revenue, profit, discount impact, customer activity, and promotion performance through interactive visualizations and KPIs.

---

## Business Problem

Retail organizations generate large volumes of transactional data from customers, products, and promotional campaigns. Without proper analysis, it becomes difficult to identify profitable products, evaluate promotional strategies, and understand customer purchasing patterns.

This project addresses questions such as:

- Which products generate the highest revenue?
- Which promotions are most effective?
- How do discounts affect profitability?
- Which customer segments contribute the most sales?
- How do sales trends change over time?

---

## Dataset Information

| Attribute | Details |
|------------|---------|
| Dataset | Store Sales Dataset |
| Records | 3,510 |
| Data Source | Excel |
| Visualization Tool | Power BI |
| Domain | Retail Analytics |

### Data Model

The project follows a **Star Schema** consisting of:

### Fact Table

- Order ID
- Date
- Customer ID
- Product ID
- Promotion ID
- Units Sold
- Price Per Unit
- Total Sales
- Discount Percentage
- Discount Value
- Net Sales
- Profit

### Dimension Tables

- Customer
- Product
- Promotion
- Date

---

## Dashboard Features

### Sales Overview

- Revenue Analysis
- Profit Analysis
- Sales Trend Analysis
- Customer Performance

### Product Analysis

- Product Sales Ranking
- Product Profitability
- Category Performance

### Promotion Analysis

- Promotion Effectiveness
- Discount Analysis
- Revenue Impact
- Profit Comparison

### Customer Analysis

- Customer Purchase Trends
- Sales Distribution
- Customer Contribution Analysis

---

## KPIs Used

- Total Sales
- Net Sales
- Total Profit
- Units Sold
- Average Sales Value
- Discount Percentage
- Discount Value
- Average Profit

---

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Excel
- Star Schema Data Modeling

---

## Data Preparation

The dataset was prepared before visualization by:

- Importing sales data into Power BI.
- Designing a Star Schema data model.
- Creating relationships between fact and dimension tables.
- Validating data types.
- Creating calculated measures using DAX.
- Organizing transactional data for efficient reporting.

---

## Dashboard Pages

### 1. Sales Overview

Provides an overview of total sales, revenue, profitability, and sales trends.

### 2. Product Performance

Analyzes product-wise sales, profitability, and contribution to overall revenue.

### 3. Promotion Analysis

Evaluates promotional campaigns by comparing discount values, sales performance, and profit generation.

### 4. Customer Analysis

Examines customer purchasing behavior, sales contribution, and transaction patterns.

---

## Key Insights

- Promotional campaigns increase sales volume but can reduce profit margins if discounts are too high.
- A small number of products contribute significantly to total revenue.
- Customer purchasing behavior varies across different promotional campaigns.
- Profitability depends on balancing pricing strategy with discount offers.
- The Star Schema improves reporting performance and enables scalable business analysis.

---

## Challenges Solved

During the development of this project, the following challenges were addressed:

- Designed and implemented a Star Schema data model.
- Created relationships between multiple dimension tables.
- Developed reusable DAX measures for sales KPIs.
- Built interactive reports with slicers and filters.
- Structured sales data for efficient analysis and reporting.

---

## Dashboard Preview

### Sales Overview

![Sales Overview](https://github.com/Sameer0166/Retail-Sales-Promotion-Analysis/blob/main/Page%201.png)

### Product Analysis

![Product Analysis](https://github.com/Sameer0166/Retail-Sales-Promotion-Analysis/blob/main/Page%202.png)

### Promotion Analysis

![Promotion Analysis](https://github.com/Sameer0166/Retail-Sales-Promotion-Analysis/blob/main/Page%203.png)

---

## Skills Demonstrated

- Business Intelligence
- Retail Analytics
- Sales Analytics
- Customer Analytics
- Promotion Analysis
- Star Schema Data Modeling
- Power BI
- Power Query
- DAX
- Dashboard Design

---

## Future Improvements

Potential enhancements include:

- Customer segmentation using RFM analysis.
- Sales forecasting using time series models.
- Market basket analysis for product recommendations.
- Regional sales performance comparison.
- Integration with live retail transaction data.

---

## Author

**MOHD SAMEER PASHA**

B.Tech Computer Science & Engineering

Aspiring Data Analyst | Power BI Developer

GitHub: https://github.com/Sameer0166

---

⭐ If you found this project useful, consider giving this repository a star.
