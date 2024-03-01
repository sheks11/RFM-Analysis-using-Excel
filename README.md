# RFM Analysis for Customer Segmentation using Excel
This repository contains the source data, analysis and documentation for Customer Segmentation using RFM Analysis.

## Project Overview

This project involves the implementation of RFM analysis, which stands for Recency, Frequency, and Monetary Value analysis, to effectively segment and profile customers. The primary objective is to gain valuable insights into customer purchasing behavior, enabling the creation of targeted marketing strategies tailored to the unique characteristics of each customer segment.

## Dataset

The project utilized a dataset from Kaggle containing information on 793 customers, organized in 21 columns. These columns include various pieces of information about each customer, including a unique Customer ID, Order ID, Order Date, Amount Spent etc.

## Methodology

For this project, I used Microsoft Excel for data transformation, analysis, and visualization. Here's a brief overview of the methodology:

**1) Data Transformation:** Created new columns displaying the total monetary value spent, most recent order date, and total number of orders of each customer using pivot table. With the most recent order date available, we calculate the number of days since last order by using datedif function

**2) Percentrank:** Created new columns for Percentrank values for Recency, Frequency, and Monetary Value to normalize these metrics.

**3) Create RFM Score:** Calculated the RFM score based on the Percentrank values. Created a new column for Percentrank.inc of the RFM score.

**4) Customer Segmentation:** Created a new column for "Customer Segment" and segmented customers based on the RFM score using VLOOKUP.

**5) Summary:** Summarized the purchasing behavior of customers in each segment using pivot table.

**6) Visualization:** Created a pie chart displaying the count of customers in each segment, and created other visualizations explaining the purchasing behavior of customers in each segment.

## Recommendations

Based on the analysis, the following recommendations were made for the marketing strategies:

**Top Customers:**

1) Exclusive Offers: Provide special offers or discounts exclusively for top customers.
2) Personalized Recommendations: Offer personalized product recommendations based on their purchase history.
3) Priority Support: Offer priority customer support to enhance their loyalty.
4) Loyalty Program: Consider implementing a loyalty program to reward continued patronage.

**At Risk/Need Attention and Immediate Attention Customers Combined:**

1) Re-Engagement Campaign: Launch a re-engagement campaign with special offers or discounts.
2) Feedback Request: Ask for feedback on previous experiences to rekindle interest.
3) Customer Service Outreach: Proactively reach out to address any past issues.
4) Win-Back Offers: Offer attractive win-back offers for customers who haven't made a purchase in a while.

## References
Please use these references for a deeper understanding of the analysis
1) [Medium Article](https://medium.com/@okon.judith/rfm-analysis-for-customer-segmentation-and-profiling-using-excel-4b837b49cbcb)
2) [Youtube](https://youtu.be/0BwBJvGAovI?si=OcyA9ti8axCfXD86)
