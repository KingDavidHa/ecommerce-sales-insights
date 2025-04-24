# E-commerce Sales Data Project

This project provides a comprehensive analysis of international e-commerce sales, combining data preparation, time series forecasting, customer segmentation, and business intelligence. Built with a focus on executive-level insights and strategic decisions.

---

## Chapter 1: Data Loading and Preparation

- Imported and explored raw sales data
- Cleaned missing values and standardized formats
- Converted date formats and extracted time-based features (year, month, quarter)
- Handled outliers and performed data quality checks
- Summary metrics:
  - Total Sales: $6.47M
  - Total Pieces Sold: 9,918
  - Date Range: 2021-01-07 to 2022-12-04

---

## Chapter 2: Time Series Analysis

- **Monthly Sales Trends**:
  - Highest: April 2021 ($875K)
  - Lowest: October 2021 ($40K)
  - Total Sales Growth: -38.4%
  - Avg MoM Growth: +109.2%

- **Seasonality**:
  - Peak Month: May (17.6% of total sales)
  - Peak Quarter: Q2 (41.3% of total sales)
  - Variation Ratio: 11.5x between best/worst months

- **Forecasting**:
  - ARIMA(1,0,1) Model
  - Time series tested stationary (ADF p-value: 0.0036)
  - Forecasts generated with confidence intervals

- **Weekday Analysis**:
  - Best Day: Thursday ($1.45M)
  - Worst Day: Sunday ($385K)
  - 3.75x variation between days

- **Integrated Metrics**:
  - Tracked monthly customer/product dynamics
  - Calculated correlations between sales, orders, AOV

---

## Chapter 3: Customer Analysis

- **Customer Overview**:
  - 76 unique customers
  - Avg Sales per Customer: ~$85K
  - Top 10 customers drive 57.5%+ of total revenue

- **Pareto Principle Validated**:
  - ~20% of customers generate 80% of revenue

- **RFM Segmentation**:
  - Recency: Days since last purchase
  - Frequency: Order count
  - Monetary: Total sales value
  - Customers scored and segmented (1–5 scale)

---

## Tech Stack

- Python (pandas, seaborn, matplotlib, statsmodels, scikit-learn)
- Jupyter Notebook
- ARIMA time series modeling
- Plotly (optional for interactive visualizations)

---

## Project Goals

- Identify sales trends, growth opportunities, and high-value customers
- Build sales forecasting models to anticipate future performance
- Use data-driven segmentation for targeted marketing strategies

---
