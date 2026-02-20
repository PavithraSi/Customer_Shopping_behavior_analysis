# Customer_Shopping_behavior_analysis
End-to-end retail analytics project analyzing 3,900 customer transactions using Python, PostgreSQL, SQL, and Power BI to uncover revenue drivers, customer segmentation patterns, and subscription impact.
Customer Shopping Behavior Analysis

This project focuses on analyzing customer shopping data to understand purchasing patterns, revenue drivers, and customer behavior. The goal was to simulate a real-world analytics workflow starting from raw data and ending with business insights and dashboard visualization.

I used Python for data cleaning and exploratory analysis, PostgreSQL for structured data storage, SQL for business queries, and Power BI to create an interactive dashboard.

Project Objective

The main objective of this project was to answer practical business questions such as:

Which product categories generate the most revenue?

Do subscription customers spend more than non-subscription customers?

How does purchase frequency affect overall spending?

Which customer segments contribute the most to revenue?

The focus was not just on cleaning data, but on extracting insights that could support business decision-making.

Dataset Overview

The dataset contains 3,900 customer transaction records with 18 attributes, including:

Customer demographics (Age, Gender, Location)

Purchase details (Category, Item, Season, Purchase Amount)

Behavioral data (Previous Purchases, Frequency of Purchases)

Engagement indicators (Review Rating, Subscription Status)

Data Cleaning and Preparation

Using Python (Pandas), I performed the following steps:

Identified and handled missing values in the review_rating column using median imputation based on product category.

Standardized column names to snake_case for consistency.

Verified and removed redundant columns (promo_code_used) after confirming duplication.

Created new features such as:

age_group for demographic segmentation

purchase_frequency_days to convert categorical frequency into numeric values

These steps ensured the dataset was clean, structured, and ready for deeper analysis.

Exploratory Data Analysis (EDA)

During EDA, I explored:

Distribution of purchase amounts

Age distribution of customers

Category-wise purchase trends

Gender-based revenue contribution

Relationship between previous purchases and spending

One important observation was that customers with higher previous purchases tend to have higher spending, indicating potential for loyalty or retention programs.

Database Integration

To simulate a real-world workflow, I connected Python to PostgreSQL using SQLAlchemy and loaded the cleaned dataset into a relational table.

This allowed structured querying and separated data preparation from analysis, similar to how enterprise systems operate.

SQL Analysis

Using SQL, I performed business-oriented queries such as:

Total revenue by category

Average spending by subscription status

Revenue distribution by gender

Payment method usage

Seasonal sales comparison

These queries helped translate raw data into measurable business insights.

Power BI Dashboard

I created an interactive Power BI dashboard to visualize:

Total Revenue

Average Purchase Amount

Customer Distribution

Revenue by Category

Revenue by Gender

Seasonal Trends

Payment Method Usage

The dashboard allows users to explore insights dynamically instead of relying only on static reports.

Key Insights

Certain product categories contribute significantly more revenue than others.

Subscription customers show more consistent purchasing behavior.

Frequent buyers generate higher overall revenue.

Seasonal variations impact category performance.

Digital payment methods are widely preferred.

Business Recommendations

Based on the analysis:

Improve subscription-based incentives to increase recurring revenue.

Introduce loyalty programs targeting high-frequency customers.

Optimize marketing campaigns based on seasonal patterns.

Personalize offers using demographic segmentation.

Tools Used

Python (Pandas, NumPy)

PostgreSQL

SQL

Power BI

Git & GitHub

What This Project Demonstrates

End-to-end data analytics workflow

Data cleaning and transformation skills

Exploratory data analysis

SQL-based business querying

Dashboard development

Translating data into actionable insights
