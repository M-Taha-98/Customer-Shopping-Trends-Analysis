[![👉View Report on Notion](https://img.shields.io/badge/View%20Report%20on-Notion-black?logo=notion&logoColor=white)](https://www.notion.so/Customer-Shopping-Trend-Analysis-1ed78d64687e80c496ddcfd8e657826a?pvs=4)

# Customer Shopping Trends Analysis
An exploration of retail chain's customer shopping behaviours and preferences to create a targeted marketing strategy for the upcoming season.

# Project Overview
The management at retail chain is looking to use their customer purchase information to understand purchase patterns, analyze customer segments, and create a targeted marketing strategy for the upcoming season.
The project is undertaken to analyze this dataset, generate meaningful business insights and prepare a stakeholder dashboard to present the findings effectively.

# Data Source
The primary data used for this project is the "raw data.csv" file which records each sale transaction, along with customer review rating, purchase frequecy etc.

# Dataset Description:

The dataset contains retail transaction data with the following features:

- Customer ID - Unique identifier for each customer
- Age/Gender - Customer details
- Item Purchased - The item purchased by the customer
- Category - Category of the item purchased
- Purchase Amount (USD) - The amount of the purchase in USD
- Location - Location where the purchase was made
- Size - Size of the purchased item
- Color - Color of the purchased item
- Season - Season during which the purchase was made
- Review Rating - Rating given by the customer for the purchased item
- Subscription Status - Indicates if the customer has a subscription (Yes/No)
- Shipping Type - Type of shipping mode chosen by the customer
- Discount Applied - Indicates if a discount was applied to the purchase (Yes/No)
- Promo Code Used - Indicates if a promo code was used for the purchase (Yes/No)
- Previous Purchases - The total count of previous transactions made by the customer, excluding the current transaction
- Payment Method - Customer's preferred payment method
- Frequency of Purchases - Frequency at which the customer makes purchases (e.g., Weekly, Fortnightly, Monthly)

# Tools Used
- Power BI

# Data Preparation/Cleaning
In the initial data preparation stage, following tasks are performed:

Data loading and inspection
Data validation
Data cleaning and formatting
Handling missing and duplicate values
Adding custom features

# Exploratory Analysis
In this stage, the data was explored to identify data’s structure, quality, and limitations:

Data Profiling/ Initial Data Diagnostics/Data Summarization: descriptive statistics, cardinality check, data type inspection, correlation analysis.

# Data Analysis
The analysis step involved performing bivariate and multivariate analysis to explore how different features affect Sales/Profit as well as other features.

Few of the dimensions and relationships explored are:

Which product categories and sub-categories are leading in revenue generation and those performing poorly.
Impact of discount variability on margins across different product categories, and identifying profitable discount thresholds.
Time series analysis: time-based trends in category level performance.
Identifying customer segments that bring in the most volume and profit.
Regional performance disparities.
Analyzing performance of different ship modes and order delays to narrow logistical inefficiencies.

# Results/Findings
The insights are presented for key business areas:

Seasonal Trend
Overall Product Performance
Product Portfolio Analysis
Regional Analysis
Customer Segmentation
Discount Effectiveness
Ship Mode and Delays Trend

# Recommendations
Based on the analysis, tailored actionable business recommendations are made categorized as follows:

Product Strategy
Regional Customer Growth and Retention
Discount Optimization
Addressing Logistical Shortcomings

# Limitations
The following assumptions and caveats are notified:

It is assumed that the discount value in each transaction record is applied to the total quantity purchased, not just to a single unit.
The absence of cost-related data—specifically unit cost price (COGS) and logistics costs limits the ability to fully explain certain observations.
