#  E‑Commerce Transactions Analysis
## Overview
This project analyzes E‑Commerce Transactions sourced from Kaggle, focusing on sales trends, purchase amounts, product category performance, geographic revenue distribution, payment preferences, and customer segmentation. The goal is to uncover patterns, highlight consumer behavior, and provide actionable marketing recommendations based on transaction insights.


## Dataset & Preprocessing
### Dataset Source
Based on global e‑commerce transaction records.
Obtained from Kaggle: [E‑Commerce Transactions Dataset](https://www.kaggle.com/datasets/smayanj/e-commerce-transactions-dataset)

Contains:
- 10 columns and 50,000 rows
- Columns:
- Transaction_ID
- User_Name
- Age
- Age_Group
- Country
- Product_Category
- Purchase_Amount
- Payment_Method
- Transaction_Date
- Month

### Preprocessing Steps
- **Duplicates Removed**: 7 duplicate records were identified and removed.
- **Date Transformation**: Extracted Month from Transaction_Date and formatted months in chronological order.
- **Age Grouping**: Created Age_Group from Age and ordered age groups logically.
- **Currency Formatting**: Converted Purchase_Amount to USD ($) format.
- **Standardization**: Ensured consistent entries in Product_Category and Payment_Method.

## Data Flow into Excel
- **Raw Data Import**: Dataset loaded into Excel.
- **Transformations**: Applied cleaning steps and created structured tables.
- **Modeling**: Used pivot tables for aggregations and analysis.
- **Visualizations**: Built charts, KPIs, and slicers to highlight key findings.

## Key Findings
### Transaction Summary
|Metric | Value | 
|:---  |---:  | 
|Total Transactions  | 50K | 
| Total Sales |  $25.16M| 

### Top Product Category
- Sports generated $3.2M in revenue, making it the highest‑earning category.

### Geographic Distribution
- France contributed the most revenue, totaling $2.55M.

### Payment Preferences
- Cash on Delivery (COD) was the most popular payment method, accounting for $4.28M in purchases.

### Seasonal Trends
| Month | Sales($M) | 
|:---  |---:  | 
|January  | 2.16 | 
|February  |  1.97| 
|March  | 2.09 | 
|April  |2.09  | 
| May | 2.12 | 
|  June| 2.04 | 
| July |  2.17| 
|August  | 2.11 | 
| September |2.06  | 
|October  | 2.13 | 
|  November| 2.08 | 
| December| 2.13 |

- Peak Month: July ($2.17M)
- Lowest Month: February ($1.97M)
- Sales remained relatively stable across the year, with slight seasonal variations.

### Customer Segmentation
- The majority of transactions came from young adults aged 18–35, making this group the most engaged demographic.

## Visualizations
Screenshots of the Excel dashboard are included in the /Screenshots folder:
- Sales Trends by Month
<p align="center">
  <img src="https://github.com/Michelle167/E-commerce-Sales-Trend-Analysis/blob/main/Screenshots/Sales%20By%20Month.png?raw=true" width="500"/>
</p>

- Top Product Categories
<p align="center">
  <img src="https://github.com/Michelle167/E-commerce-Sales-Trend-Analysis/blob/main/Screenshots/Sales%20By%20Product%20Category.png?raw=true" width="500"/>
</p>

- Country Revenue Distribution
<p align="center">
  <img src="https://github.com/Michelle167/E-commerce-Sales-Trend-Analysis/blob/main/Screenshots/Sales%20By%20Country.png?raw=true" width="500"/>
</p>

- Payment Method Breakdown
<p align="center">
  <img src="https://github.com/Michelle167/E-commerce-Sales-Trend-Analysis/blob/main/Screenshots/Sales%20By%20Payment%20Method.png?raw=true" width="500"/>
</p>

## Full Dashboard Access
For interactive exploration, download the Excel dashboard here:

[Download Excel Dashboard](https://github.com/Michelle167/E-commerce-Sales-Trend-Analysis/blob/main/Dashboard/E-commerce%20Dashboard.xlsx)

## Insights & Recommendations
### Key Insights
- **Top Product Category**: Sports generated $3.2M, making it the highest‑earning category.
- **Geographic Distribution**: France contributed the most revenue at $2.55M, followed closely by Canada and the USA.
- **Payment Preferences**: Cash on Delivery dominated with $4.28M in purchases, showing strong reliance on COD.
- **Seasonal Trends**:
- **Peak Month**: July ($2.17M)
- **Lowest Month**: February ($1.97M)
- Sales remained relatively stable across the year, with slight seasonal variations.


### Recommendations
- **Marketing Focus**: Prioritize campaigns around Sports products, leveraging their $3.2M revenue lead.
- **Regional Strategy**: Strengthen marketing and inventory planning in France, USA, and Canada, the top revenue contributors.
- **Payment Optimization**: Introduce incentives for digital payments to reduce reliance on COD ($4.28M).
- **Seasonal Planning**: Prepare inventory and promotions ahead of July peaks, while addressing February’s dip with targeted campaigns.



## Conclusion
This project provides a comprehensive analysis of global e‑commerce transactions using Kaggle data and Excel. By cleaning and transforming the dataset, visualizing key metrics, and uncovering trends in product performance, geography, payment behavior, seasonality, and customer demographics, it delivers actionable insights for marketing and operational strategy.
The findings emphasize the importance of targeting young adults (18–35), leveraging seasonal demand (July peaks, February dips), and promoting digital payments. These strategies are crucial for driving growth, improving customer satisfaction, and strengthening competitiveness in the e‑commerce landscape.
