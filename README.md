# Online Retail Exploratory Data Analysis Project

## Project Overview

This repository contains an exploratory data analysis of an online retail dataset, examining transactional data from 2010-2011. The analysis provides insights into sales trends, customer behavior, popular products, and geographic distribution of sales to support data-driven business decisions.

## Dataset

The analysis uses the "Online Retail" dataset containing transactional records with the following fields:
- **InvoiceNo**: Invoice number of the transaction
- **StockCode**: Unique code of the product
- **Description**: Description of the product
- **Quantity**: Quantity of the product in the transaction
- **InvoiceDate**: Date and time of the transaction
- **UnitPrice**: Unit price of the product
- **CustomerID**: Unique identifier of the customer
- **Country**: Country where the transaction occurred

## Project Structure

```
online-retail-eda/
│
├── analysis/
│   ├── online_retail.ipynb          # Main Jupyter notebook with analysis code
│   └── Online Retail Analysis.pdf   # PDF report of findings and recommendations
│
├── data/
│   └── Online Retail.xlsx           # Raw dataset
│
├── visualizations/
│   ├── monthly_sales_trend.png      # Monthly sales trends visualization
│   ├── day_of_week_sales.png        # Sales by day of week visualization
│   ├── top_products.png             # Top 10 products visualization
│   └── top_countries.png            # Top 10 countries visualization
│
├── README.md                        # Project overview and instructions
└── requirements.txt                 # Required Python packages
```

## Key Analyses

The project includes the following key analyses:

1. **Data Cleaning and Preparation**
   - Handling missing values
   - Removing duplicates
   - Filtering out invalid transactions
   - Feature engineering for time-based analysis

2. **Sales Trend Analysis**
   - Monthly sales patterns across 2010-2011
   - Day-of-week sales distribution
   - Identification of peak sales periods

3. **Product Analysis**
   - Identification of top-selling products
   - Special focus on December/holiday season products
   - Analysis of product popularity across markets

4. **Geographic Analysis**
   - Distribution of sales across countries
   - Identification of high-potential international markets
   - Market penetration assessment

5. **Outlier Analysis**
   - Detection of unusual order quantities
   - Investigation of large-volume transactions
   - Assessment of potential data anomalies

## Key Findings

- Sales demonstrate clear seasonal patterns with peaks in January, March, and December
- Thursdays show the highest sales volume among all days of the week
- Gift items and decorative products dominate the top-selling list
- The United Kingdom is the primary market, with the Netherlands leading international sales
- A small percentage of products and customers account for a large portion of total revenue

## Recommendations

Based on the analysis, several business recommendations were developed:

1. **Sales Strategy**
   - Implement targeted promotions on Thursdays
   - Develop seasonal marketing campaigns aligned with peak months
   - Focus resources on top-performing products and customer segments

2. **Inventory Management**
   - Prioritize stocking of consistently popular products
   - Develop seasonal forecasting for holiday periods
   - Optimize inventory levels based on day-of-week patterns

3. **International Expansion**
   - Target high-potential markets including the Netherlands, Ireland, and Germany
   - Develop market-specific strategies based on regional preferences
   - Investigate success factors in distant markets like Australia

## Technologies Used

- **Python 3.x**
- **Libraries**:
  - pandas: Data manipulation and analysis
  - matplotlib/seaborn: Data visualization
  - numpy: Numerical computing

## Future Work

Potential extensions to this analysis include:
- Customer segmentation using RFM (Recency, Frequency, Monetary) analysis
- Market basket analysis to identify product associations
- Customer lifetime value calculation
- Predictive modeling for sales forecasting
- Churn prediction and customer retention analysis

