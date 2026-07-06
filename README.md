# Retail Business Analytics Dashboard

An end-to-end collaborative analytics project built using **Python** and **Power BI** to demonstrate practical business analytics, marketing analytics, supply chain analytics, demand forecasting, and dashboard development skills using a real-world retail dataset.

---

# Project Goal

The objective of this project was to analyze an online retail business using transactional sales data and transform it into meaningful business insights through data analytics and visualization.

The project focuses on:

- Understanding customer behavior and purchasing patterns
- Evaluating revenue and sales performance
- Improving inventory planning and product prioritization
- Forecasting future demand
- Developing interactive dashboards for executive decision-making


---

# Project Workflow

```text
Raw Retail Dataset
        │
        ▼
Python Data Cleaning & ETL
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
 ┌───────────────┬────────────────┐
 │               │                │
Marketing     Supply Chain     Executive KPIs
 Analytics      Analytics
 │               │
 └───────────────┴────────────────┘
        │
        ▼
Power BI Dashboard Development
        │
        ▼
Business Insights & Recommendations
```

---

# Data Cleaning & ETL

The raw Online Retail dataset was cleaned and transformed using Python (Pandas) to ensure high-quality data for analysis.

Cleaning activities included:

- Removed duplicate transactions
- Removed cancelled invoices
- Removed negative quantities
- Removed zero-priced transactions
- Removed missing Customer IDs
- Removed missing product descriptions
- Removed administrative/non-sales products
- Converted invoice dates into datetime format
- Created a clean master dataset
- Engineered new business variables including:
  - Revenue
  - Year
  - Month
  - Month-Year
  - Customer metrics
  - Product metrics
  - Product categories

---

# Marketing Analytics

The marketing analysis focused on customer behavior and sales performance.

### Customer Analytics

Developed business KPIs including:

- Total Customers
- Total Orders
- Average Order Value
- Revenue per Customer
- Purchase Frequency

### RFM Customer Segmentation

Customers were segmented using:

- Recency
- Frequency
- Monetary Value

Customer segments include:

- Champions
- Loyal Customers
- Regular Customers
- At Risk Customers
- Lost Customers

### Market Basket Analysis

Performed Association Rule Mining to identify products frequently purchased together.

Business applications include:

- Cross-selling
- Product bundling
- Promotional campaigns
- Customer retention strategies

---

# Supply Chain Analytics

The supply chain analysis focused on demand forecasting and inventory optimization.

### Demand Analysis

- Monthly demand trends
- Category performance
- Quantity sold analysis
- Revenue contribution analysis
- Fast-moving products
- Slow-moving products

### Time Series Forecasting

Developed:

- Linear Trend Model
- Holt-Winters Forecasting Model

Forecast accuracy was evaluated using:

- Mean Absolute Percentage Error (MAPE)
- Mean Absolute Deviation (MAD)
- Mean Squared Deviation (MSD)

### Inventory Planning

Performed:

- ABC Inventory Classification
- Forecast Demand
- Safety Stock Calculation
- Reorder Point Calculation
- Inventory Priority Recommendations

---

# Power BI Dashboards

Three interactive dashboards were developed to communicate business insights.

## Executive Dashboard

Provides an overall business performance summary including:

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Total Products
- Revenue Trends
- Country Performance
- Product Category Performance
- Top Products

---

## Marketing Dashboard

Focuses on customer analytics including:

- RFM Customer Segmentation
- Customer Value Analysis
- Market Basket Analysis
- Revenue Contribution by Segment
- Customer Purchasing Behaviour

Supports:

- Customer retention
- Campaign targeting
- Cross-selling strategies

---

## Supply Chain Dashboard

Provides operational insights including:

- Demand Trends
- Holt-Winters Forecast
- Linear Trend Analysis
- ABC Classification
- Inventory Planning
- Safety Stock
- Reorder Points
- Product Priority Recommendations

Supports:

- Inventory optimization
- Forecasting
- Replenishment planning


# Skills Demonstrated

This project demonstrates practical experience with:

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Mlxtend
- Data Cleaning
- ETL
- Feature Engineering
- Exploratory Data Analysis
- Business KPI Development
- Customer Segmentation
- RFM Analysis
- Market Basket Analysis
- Demand Forecasting
- Holt-Winters Forecasting
- Linear Trend Analysis
- Inventory Planning
- ABC Inventory Classification
- Power BI Dashboard Development
- Business Storytelling
- Team Collaboration

---

# Key Business Insights

The project identified several actionable insights, including:

- Revenue exhibits clear seasonal trends with increased demand during peak periods.
- A small proportion of products contributes the majority of total revenue, supporting inventory prioritization using ABC classification.
- High-value customer segments can be targeted through personalized marketing campaigns.
- Frequently purchased product combinations present opportunities for cross-selling and promotional bundling.
- Holt-Winters forecasting provides reliable demand estimates to support inventory planning.
- Safety stock and reorder point calculations improve replenishment decisions and reduce stock-out risk.

---

# Repository Structure

```text
Retail-Business-Analytics-Dashboard
│
├── README.md
├── requirements.txt
│
├── data
│   ├── cleaned_online_retail.xlsx
│   └── Retail_Categorized.xlsx
│
├── notebooks
│   ├── Marketing_Analysis.ipynb
│   └── Supply_Chain_Analysis.ipynb
│
├── powerbi
│   ├── Executive_Dashboard.pbix
│   ├── Marketing_Dashboard.pbix
│   └── Supply_Chain_Dashboard.pbix
│
└── images
    ├── Executive_Dashboard.png
    ├── Marketing_Dashboard.png
    └── Supply_Chain_Dashboard.png
```

---

# Contributors

This project was completed collaboratively.

### Shared Responsibilities

- Data cleaning and preprocessing
- Feature engineering
- Product categorization
- Dashboard design
- Business problem definition
- Data validation

### Marketing Analytics

- RFM Customer Segmentation
- Market Basket Analysis
- Customer Analytics
- Marketing Dashboard Development

### Supply Chain Analytics

- Time Series Analysis
- Linear Trend Analysis
- Holt-Winters Forecasting
- ABC Inventory Classification
- Inventory Planning
- Supply Chain Dashboard Development

---


