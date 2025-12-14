Customer Shopping Behavior Analysis
Overview

This project performs an end-to-end analysis of 3,900 customer shopping transactions to identify spending patterns, customer segments, product performance, and the effectiveness of subscriptions and discounts. The goal is to transform transactional data into actionable business insights using industry-standard analytics tools.

Objectives

Analyze customer demographics and purchasing behavior

Measure the impact of subscriptions and discounts on revenue

Identify high-value customer segments and repeat purchase behavior

Evaluate product performance across categories

Present insights through an interactive business dashboard

Dataset Information

Total Transactions: 3,900

Total Features: 18

Products: 25 unique items

Categories: Multiple (e.g., Clothing, Footwear, Accessories)

Locations: 50

Missing Data: 37 missing values in the review_rating column (handled during preprocessing)

Key Features

Customer demographics (age, gender, location, subscription status)

Purchase details (item, category, size, color, season, amount)

Behavioral attributes (discount usage, purchase frequency, previous purchases, review ratings, shipping type)

Tools & Technologies

Python – data cleaning, feature engineering, exploratory analysis

Pandas / NumPy – data manipulation

SQL (PostgreSQL) – analytical business queries

Power BI – interactive dashboard and visual storytelling

Data Preparation

Loaded and explored data using pandas

Handled missing review ratings using median imputation by product category

Standardized column names using snake_case

Engineered new features such as age_group and purchase_frequency_days

Removed redundant fields to improve data consistency

Loaded cleaned data into PostgreSQL for SQL analysis

Analysis Performed

Revenue analysis by gender and age group

Customer segmentation (New, Returning, Loyal) based on purchase history

Subscription vs non-subscription spending comparison

Discount usage and identification of discount-dependent products

Product performance by purchase volume and average rating

Shipping type impact on average order value

Key Insights

Subscription status does not significantly increase average order value

Loyal customers contribute the majority of total revenue

Several high-volume products rely heavily on discounts, creating margin risk

Express shipping customers show higher average purchase values

Revenue contribution is relatively balanced across age groups, with young adults leading slightly

Business Recommendations

Strengthen subscription benefits to improve conversion among repeat buyers

Focus retention efforts on high-value loyal customers

Reassess discount strategies for discount-dependent products

Promote top-rated products alongside best-sellers

Target high-revenue customer segments with tailored marketing strategies

Project Structure
├── data/                # Raw and cleaned datasets
├── notebooks/           # Python analysis and preprocessing
├── sql/                 # PostgreSQL queries
├── dashboard/           # Power BI dashboard
├── presentation/        # Project presentation
└── README.md

Conclusion

This project demonstrates a full analytics workflow — from raw data to business insight — with a strong emphasis on decision-making, not just visualization.
