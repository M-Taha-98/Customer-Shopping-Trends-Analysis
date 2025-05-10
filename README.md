[![👉View Report on Notion](https://img.shields.io/badge/View%20Report%20on-Notion-black?logo=notion&logoColor=white)](https://www.notion.so/Customer-Shopping-Trend-Analysis-1ed78d64687e80c496ddcfd8e657826a?pvs=4)

# Customer Shopping Trends Analysis
###### An exploration of retail chain's customer shopping behaviours and preferences to create a targeted marketing strategy for the upcoming season

![Customer shopping trend](https://github.com/user-attachments/assets/073c195e-2ad4-41bb-b3d1-922f926a8e4a)
___

## Project Overview
The management at retail chain is looking to use their customer purchase information to understand purchase patterns, analyze customer segments, and create a targeted marketing strategy for the upcoming season.
The project is undertaken to analyze this dataset, generate meaningful business insights and prepare a stakeholder dashboard to present the findings effectively.

## Data Source
The primary data used for this project is the "raw data.csv" file which records each sale transaction, along with customer review rating, purchase frequecy etc.

## Dataset Description:

The dataset contains retail transaction data with the following features:

- Customer ID - Unique identifier for each customer
- Age/Gender - Customer details
- Item Purchased - The item purchased by the customer
- Category/Size/Color - Product details
- Purchase Amount (USD) - The amount of the purchase in USD
- Location - Location where the purchase was made
- Season - Season during which the purchase was made
- Review Rating - Rating given by the customer for the purchased item
- Subscription Status - Indicates if the customer has a subscription (Yes/No)
- Shipping Type - Type of shipping mode chosen by the customer
- Discount Applied - Indicates if a discount was applied to the purchase (Yes/No)
- Promo Code Used - Indicates if a promo code was used for the purchase (Yes/No)
- Previous Purchases - The total count of previous transactions made by the customer, excluding the current transaction
- Payment Method - Customer's preferred payment method
- Frequency of Purchases - Frequency at which the customer makes purchases (e.g., Weekly, Fortnightly, Monthly)

## Tools Used
- Power BI

## Data Preparation/Cleaning
Initial data cleaning/transformation is performed in Power Query:

- Renaming columns to meaningful headers.
- Removing extra columns which are not required.
- Splitting of columns such as Color-Size into two.
- Data type correction for required columns.
- Adding custom columns: Age binning:
  
  ![image](https://github.com/user-attachments/assets/d2583039-474a-4e8d-8872-12ad94c368fd)

  

## Exploratory Analysis
In this stage, the data was explored to identify data’s structure, quality, and limitations:

Data Profiling/ Initial Data Diagnostics/Data Summarization: descriptive statistics, cardinality check, data distribution through histogram.

## Data Analysis
The analysis step is divided into three separate business domains: Customer Demographics Analysis, Product and Category Analysis, and Geographical Analysis.

#### Customer Demographics Analysis
- Age distribution of the customer base.
- Age group showing the highest loyalty measured by total previous purchases, and making the most high-value purchases.
- Purchase frequency variation across genders.

#### Product and Category Analysis
- Identifying product categories bringing in the highest revenue.
- Seasonal Trends: Analyze the purchase trends by season to see which seasons have the highest spending.

#### Geographical Analysis
- Location-Based Analysis: Mapping of areas with purchase amount to highlight areas with highest sales.
- Analyzing the preference of different shipping modes areas bringing in the most business.
  
## Results/Findings
The insights are presented in form of a completely **dynamic stakeholder dashboard** with interactive filtering through slicers to allow management to easily filter and explore specific segments.

*Dashboard Snapshot:*

![image](https://github.com/user-attachments/assets/32e52ddb-22a1-4331-9a6e-53a627f09415)


## Recommendations
Based on the analysis, tailored actionable business recommendations are made categorized as follows:

- Personalization & Customer Engagement
- Customer Growth and Retention
- Loyalty Program Enhancements
- Regional Strategy

## Limitations
The following caveats are notified:

- The lack of cost-related data—particularly unit cost price and logistics expenses restricts the ability to fully interpret certain findings.
- This also constrains the analysis of profitability at both the individual order level and overall, thereby limiting insights into profit margins.
___
[View my Linkedin](https://www.linkedin.com/in/mohammadtaha-businessanalytics/)
