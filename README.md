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
* CTR%
