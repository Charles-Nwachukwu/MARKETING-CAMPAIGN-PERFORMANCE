# MARKETING-CAMPAIGN-PERFORMANCE
Marketing Campaign Performance dataset encompasses of digital marketing campaign performance across different channels: Email, Instagram Ads, Influencer Marketing, and more. Meant to track campaign performance made from Nov. 2024 - Feb. 2025 program
# Project  Overview
This dataset tracks the performance of online marketing campaigns across multiple campaigns across multiple products. It is primarily used to monitor ad efficiency, 
revenue generation, and ROI, while providing insights into campaign trends over time.

# Data Source
Marketing Campaign Analytics Team: The dataset comprises 1,000 recorded digital marketing campaign performance in 2025, covering performance across channels and product. It includes structured attributes such as total revenue, sum of ROI, total click, total impression,  total ad spent, total conversion, total revenue across revenue, total ad spent across marketing channel, conversion by category, ROI by Category, click vs impression analysis, and time based analysis for clicks, conversion, ROI and ad spend.

# Problem Statement
Stakeholders seek to address challenges such as:
* Identifying marketing channels where ads were spent on more
* Tracking product performance by total revenue
* The relationship between click and impression performance
* Evaluating time based trend for clicks, conversion, ROI and ad Spend.
  
# Tools & Methodology
Tools used:
* Power Query
* Power BI

# Data Collection
Data was aggregated from multiple sources including: Ad spent, category and product view, marketing channel, clicks, impressions, and conversions. This ensured a comprehensive view of revenue performance, sum of ROI, total Ad spent performance. 

# Data Cleaning & Preparation
To improve data quality and reliability, the following steps were preformed:
* Removal of duplicate transaction and reservation records
* Correction of inconsistent date and time formats
* Standardization of category and product names
* Validation of revenue figures to eliminate entry errors

# Data Transformation & Processing
To support deeper analysis, several transformation were applied:
* Creation of a dedicated Date Table: in Power BI for campaign date analysis
* Breakdown of campaign dates: into Year, Month, Day, Month Number, and Quarter
* Organization of date fields: to enable chronological sorting and time-based analysis

# Calculated Fields & DAX Measures
Within the BI environment, calculated metrics were developed to quality performance, including:
* Total Clicks
* Total Impression
* Total Revenue
* Conversion Rate (CR%)
* Total Conversion
* ROI%
* Total Ad Spend
* CTR%`

# Data Validation
Cross-checks were conducted to ensure:
* Revenue totals matched transactional aggregates
* Checking that all monetary columns used a consistent currency, ensuring accurate  calculations and comparisons during analysis
* KPI outputs were consistent across filters and segments

This validation process ensured analytical integrity

# Data Modeling
A Relational data model was created here between the marketing table and the date table (Many-One-Relationship)
![Marketing Campaign Data Model](Marketing%20Campaign%20Data%20Model.png)

# Data Visualization
Built a one page interactive dashboards that answers stakeholders questions in detail.
Interactive dashboards were developed to present:
* Clicks vs impression performance
* Top marketing channel by Ad spent
* Time based trend for ROI, clicks, conversion, and ad spent

The visualization layers was designed to support executive-level decision making through clear KPIs and comparative views.

# Exploratory Data Analysis(EDA)
An in-depth exploratory data analysis was conducted to uncover underlying performance patterns across marketing channels, product categories, products, and campaign periods. The analysis focused on advertising spend, impressions, clicks, conversions, revenue, and ROI to identify key performance drivers and areas of variation.

* Key Patterns

Initial analysis revealed noticeable differences in campaign performance across product categories and marketing channels. Household recorded the highest ROI at approximately 156, followed by Groceries (150) and Beverages (140), while Personal Care (125) recorded the lowest ROI among the categories analyzed.

Conversion rates also varied across categories, with Household achieving the highest conversion rate at approximately 11.3%, while Personal Care and Snacks recorded the lowest at approximately 8.9%.

* Marketing Channel Analysis

Advertising spend varied across marketing channels. Google Ads received the highest advertising spend at approximately $0.53M, closely followed by Referral at $0.52M. Email Campaign and Instagram Ads each accounted for approximately $0.46M, while Influencer Marketing recorded approximately $0.45M.

This highlights differences in how the advertising budget was distributed across channels.

* Product Performance

Product-level analysis revealed differences in revenue contribution. Cold Drink generated the highest revenue at approximately $19.1M, followed by Biscuits ($19.0M) and Dishwasher Liquid ($18.9M).

This analysis helped identify the products contributing the most to overall campaign revenue.

* Trends

Time-based analysis showed fluctuations in ad spend, clicks, conversions, and ROI throughout the campaign period. Click activity displayed noticeable spikes during certain periods, indicating variations in audience engagement over time.

These fluctuations provide an opportunity to investigate which campaign periods or marketing activities contributed to increases or decreases in performance.

* Engagement Analysis

The analysis also examined the relationship between impressions and clicks. The campaigns generated approximately 242M impressions and 12.34M clicks, resulting in a click-through rate of approximately 4.84%.

This provided an overview of how effectively campaign exposure translated into user engagement.

# Key Insight and Recommendations
The exploratory analysis revealed important patterns in product performance, marketing channel effectiveness, and revenue trends over time. These findings were used to identify areas of strong performance and opportunities for further optimization.

### Product Performance Analysis
Key Insight

Household emerged as the strongest-performing product category.

Household generated the highest category revenue of $82.83M.
Groceries followed with $73.84M.
Personal Care generated the lowest category revenue at $61.97M.
Household also recorded the highest ROI based on the ROI measure used in the analysis.

Recommendation

Investigate the factors driving Household's strong performance, including product demand, campaign targeting, and advertising efficiency. Successful strategies identified within this category can be evaluated for potential application to lower-performing categories.

### Top-Performing Products
Key Insight

Revenue was relatively balanced among the top-performing products.
The three highest-revenue products were:
| Product | Revenue |
| ----- | --- |
| Cold Drink | $19.13M |
| Biscuit | $19.02M  |
| Dishwasher Liquid |$18.88M |
The difference between the highest- and lowest-performing products in this group is relatively small, suggesting that overall revenue is not heavily dependent on a single product.

Recommendation

Maintain visibility and availability of these high-performing products while investigating the factors contributing to their performance. Similar characteristics can be assessed across lower-performing products to identify opportunities for improvement.

# Time-Based Trend Analysis
### Key Insight

Revenue performance varied considerably across campaign periods.

Monthly Trend

January recorded the highest monthly revenue of $127.79M.

Quarterly Trend
Q1: Revenue began at a high point before declining rapidly.
Q4: Revenue showed a steady upward trend from October through December.
Yearly Trend
2024: Revenue peaked toward the end of the year.
2025: Revenue declined at the beginning of the year.
Recommendation

Investigate the factors associated with the January revenue peak and Q4 growth, including advertising spend, clicks, conversions, product performance, and campaign activity.

The decline following the Q1 peak and the early-2025 drop should also be investigated to determine whether they were associated with changes in campaign activity, customer engagement, or other business factors.
