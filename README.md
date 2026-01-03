Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using real transactional data to understand spending patterns, product preferences, customer segments, and subscription behavior.
The insights help businesses make data-driven decisions related to marketing, pricing, and customer retention.

📊 Dataset Information

Total Records: 3,900 purchases

Total Features: 18 columns

Data Includes:

Customer details (Age, Gender, Location, Subscription Status)

Purchase details (Product, Category, Amount, Season, Size, Color)

Shopping behavior (Discounts, Ratings, Shipping Type, Purchase Frequency)

Missing Values: Review Rating column (handled during cleaning)

🧹 Data Cleaning & EDA (Python)

Performed using Python (Pandas & NumPy):

Loaded and explored the dataset

Handled missing values using median imputation

Renamed columns for better readability

Created new features like:

age_group

purchase_frequency_days

Removed redundant columns

Stored cleaned data in PostgreSQL for SQL analysis

🗄️ Data Analysis (SQL)

Business questions answered using PostgreSQL:

Revenue comparison by gender

Spending behavior of discount users

Top-rated products

Shipping type vs purchase amount

Subscriber vs non-subscriber analysis

Discount-dependent products

Customer segmentation (New, Returning, Loyal)

Revenue by age group

Repeat buyers and subscription trends

📈 Dashboard (Power BI)

An interactive Power BI dashboard was created to visualize:

Revenue trends

Customer segments

Product performance

Subscription insights

💡 Key Business Recommendations

Promote subscriptions with exclusive benefits

Introduce loyalty programs for repeat customers

Optimize discount strategies

Highlight top-rated and best-selling products

Focus marketing on high-revenue age groups

🛠️ Tools & Technologies

Python (Pandas, NumPy)

PostgreSQL

SQL

Power BI
