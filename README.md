# customer-segmentation-rfm-analysis

# Project Description

This project analyzes customer transaction data to segment customers based on their purchasing behavior. Using RFM Analysis (Recency, Frequency, Monetary) and K-Means clustering, customers are grouped into meaningful segments such as inactive, regular, loyal, and VIP customers. The analysis helps businesses better understand customer behavior and design targeted marketing and retention strategies.

# Project Overview

The goal of this project is to transform raw transactional data into customer-level insights and apply clustering techniques to identify distinct customer segments. The project follows a complete data analysis workflow, from data preparation to business recommendations.

# Objective

Create customer-level features using RFM analysis

Explore customer behavior through exploratory data analysis (EDA)

Segment customers using K-Means clustering

Provide actionable business recommendations for each segment

# Dataset

Transactional customer data in Excel format

Includes customer IDs, transaction dates, and transaction values

# Methodology
1. Data Cleaning & Preparation

- Loaded Excel data using Python

- Cleaned and formatted data for analysis

- Aggregated transactions at the customer level

2. Feature Engineering (RFM Analysis)

Created the following metrics for each customer:

- Recency: Days since last purchase

- Frequency: Number of transactions

- Monetary: Total amount spent

3. Exploratory Data Analysis (EDA)

- Analyzed distributions of RFM variables

- Identified outliers and skewness

- Explored relationships between customer engagement and spending

4. Customer Segmentation

- Scaled RFM features

- Used the Elbow Method to select the number of clusters

- Applied K-Means clustering

- Labeled clusters based on customer behavior


# Customer Segments

- Inactive / At-Risk Customers: Low engagement and long time since last purchase

- Regular Customers: Active customers with moderate frequency and spending

- Loyal High-Value Customers: Frequent and high-spending customers

- VIP / Elite Customers: Top customers with exceptional spending and engagement

# Key Insights

- Most customers have low frequency and spending

- A small group of customers contributes a large portion of total revenue

- Clear behavioral differences exist between customer segments

# Business Recommendations

- Re-engage inactive customers using targeted campaigns

- Grow regular customers through loyalty and upselling strategies

- Retain high-value and VIP customers with exclusive offers and personalized experiences


# Tools Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Google Colab

Conclusion

This project demonstrates a practical customer segmentation approach using RFM analysis and clustering, showcasing essential skills required for a Data Analyst role, including data preparation, EDA, modeling, visualization, and business insight generation.
