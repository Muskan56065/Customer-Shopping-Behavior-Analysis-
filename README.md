.

🛒 Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover insights related to customer segments, spending patterns, product performance, discount usage, and subscription behavior to support data-driven decision-making.

📊 Dataset Summary

Total Records: 3,900

Total Columns: 18

Key Features:

Customer demographics (Age, Gender, Location, Subscription Status)

Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)

Shopping behavior (Discount Applied, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type)

Missing Values: 37 missing values in the review_rating column

🧹 Data Cleaning & Exploratory Data Analysis (Python)

Data cleaning and EDA were performed using Python (Pandas) in a Jupyter Notebook environment within VS Code:

Imported and explored the dataset using df.info() and df.describe()

Handled missing values in review_rating using median imputation by product category

Standardized column names using snake_case

Created derived features:

age_group for demographic analysis

purchase_frequency_days to analyze customer buying behavior

Identified and removed redundant columns

Exported the cleaned dataset for database analysis

🗄️ Data Analysis Using MS SQL Server

The cleaned data was loaded into MS SQL Server, where SQL queries were written to answer key business questions:

Revenue analysis by gender

Identification of high-spending discount users

Top 5 products by average review ratings

Comparison of purchase behavior by shipping type

Subscriber vs. non-subscriber revenue comparison

Products most dependent on discounts

Customer segmentation (New, Returning, Loyal)

Top 3 most purchased products per category

Repeat purchase behavior and subscription trends

Revenue contribution by age group

📈 Power BI Dashboard

An interactive Power BI dashboard was created using data sourced from MS SQL Server to visualize:

Revenue trends

Customer segments

Product performance

Discount impact

Subscription behavior

💡 Business Recommendations

Strengthen subscription offerings with exclusive benefits

Introduce loyalty programs for repeat customers

Optimize discount strategies to maintain profitability

Promote top-performing products

Focus marketing on high-value customer segments

🛠️ Tools & Technologies

Python (Pandas)

Jupyter Notebook (VS Code environment)

MS SQL Server

Power BI

Git & GitHub
