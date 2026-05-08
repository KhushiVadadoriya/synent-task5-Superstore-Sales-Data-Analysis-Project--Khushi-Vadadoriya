# Superstore Sales & Customer Segmentation Analysis

> A comprehensive data analysis project uncovering business insights, revenue trends, and customer purchasing behaviors using RFM (Recency, Frequency, Monetary) analysis.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Business Insights](#key-business-insights)
- [Sales Trend Analysis](#sales-trend-analysis)
- [Category & Segment Analysis](#category--segment-analysis)
- [Customer Segmentation (RFM Analysis)](#customer-segmentation-using-rfm-analysis)
- [Technologies & Tools Used](#technologies--tools-used)
- [Visualizations Included](#visualizations-included)
- [Business Value](#business-value-of-this-project)
- [Project Structure](#project-structure)
- [Future Improvements](#future-improvements)



## Project Overview

This project analyzes Superstore sales data to uncover business insights, customer purchasing behavior, revenue trends, and customer segmentation patterns using **RFM Analysis (Recency, Frequency, Monetary)**. The goal is to help businesses make data-driven decisions for marketing, inventory management, and customer retention.

**The analysis focuses on:**
* Sales performance and KPIs
* Seasonal revenue trends
* Product category performance
* Customer segmentation using RFM analysis
* Actionable business recommendations


## Key Business Insights

### Overall Performance
* **Total Revenue:** $2,261,536.78
* **Total Orders:** 4,922
* **Total Customers:** 793
* **Average Order Value:** ~$459.48

> **Insight:** The business demonstrates a healthy customer base and strong order value, indicating stable revenue generation.


## Sales Trend Analysis

The project identifies clear seasonal patterns in sales performance.

### Major Findings
* Significant sales spikes occur during **November and December**.
* **Q4 consistently generates the highest revenue.**
* End-of-year demand strongly influences overall business performance.

### Business Recommendations
* Increase inventory preparation during Q3.
* Allocate higher marketing budgets before the holiday season.
* Launch promotional campaigns ahead of Q4 demand peaks.



## Category & Segment Analysis

### Customer Segments
The dataset contains three major customer segments: *Consumer*, *Corporate*, and *Home Office*.
> **Insight:** The **Consumer segment** contributes the highest share of total revenue.

### Top Revenue-Generating Sub-Categories
Top-performing product sub-categories include:
1. **Phones**
2. **Chairs**

These categories drive significant revenue and should be monitored closely for profitability and discount management.



## Customer Segmentation using RFM Analysis

RFM analysis categorizes customers based on:
* **Recency** → How recently a customer purchased
* **Frequency** → How often they purchase
* **Monetary Value** → How much they spend

### Customer Segments Identified

| Segment | Description |
| :--- | :--- |
| **Champions** | High-value loyal customers |
| **Potential Loyalists** | Customers likely to become loyal |
| **At Risk** | Previously valuable customers becoming inactive |
| **Needs Attention** | Low engagement customers |



## Major RFM Insights & Strategies

### Champions
* **Count:** 242 customers belong to this category.
* **Behavior:** These customers purchase frequently and spend the most.
* **Strategy:** Implement loyalty programs, offer VIP exclusives, and provide referral incentives.

### At Risk Customers
* **Count:** 154 customers are classified as At Risk.
* **Behavior:** They were previously high-value customers but have stopped purchasing recently.
* **Strategy:** Deploy personalized win-back campaigns, special discount offers, and re-engagement emails.

### Needs Attention
* **Count:** 242 customers.
* **Behavior:** Purchase infrequently and have low recent activity.
* **Strategy:** Use targeted product recommendations, retargeting campaigns, and personalized engagement.



## Technologies & Tools Used

* **Python**
* **Pandas** & **NumPy** (Data Manipulation)
* **Matplotlib** & **Seaborn** (Data Visualization)
* **Jupyter Notebook** (Analysis Environment)



## Visualizations Included

This project contains visual reports to better illustrate the findings:
* Monthly Sales Trend Line Chart
* Revenue by Customer Segment
* Top 10 Sub-Categories Revenue Chart
* RFM Customer Segment Distribution



## Business Value of This Project

This analysis empowers businesses to:
* Improve customer retention rates.
* Identify and reward high-value customers.
* Optimize inventory planning for peak seasons.
* Increase marketing efficiency through targeted campaigns.
* Understand seasonal demand patterns.
* Make strategic, data-backed business decisions.



## Project Structure
```bash
├── data/
│   └── superstore_dataset.csv
│
├── notebooks/
│   └── sales_analysis.ipynb
│
├── visuals/
│   └── charts_and_graphs/
│
├── report/
│   └── Superstore Sales & Customer Segmentation Report.docx
│
