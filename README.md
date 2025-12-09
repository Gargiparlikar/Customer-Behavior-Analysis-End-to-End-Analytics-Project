# 📊 Customer Behavior Analysis – End-to-End Analytics Project
🔍 An industry-standard business analytics project built using Python, SQL, Excel, and Power BI to uncover customer purchase patterns, demographic trends, and product preferences.
## 🖼️ Dashboard Preview



![Customer Behavior Dashboard](https://github.com/yourusername/yourrepo/assets/dashboard_image.png)

## 📌 Project Overview

This Customer Behavior Analysis project represents a complete, real-world data analytics workflow—from raw data cleaning to interactive dashboard creation. The goal of this project is to understand:

How customer demographics influence spending

Which product categories perform best

Seasonal buying behavior

How subscription, shipping, and payment choices affect purchasing

Ratings and customer satisfaction patterns

The entire analysis is visualized in a clean Power BI dashboard with KPIs and slicers for deep, on-demand insights.

## 🧠 Key Insights from the Dashboard
⭐ 1. Customer Overview

3.9K total customers

$59.76 average purchase amount

3.75 average review rating

Majority customers do not have subscriptions (73%)

⭐ 2. Product & Category Performance

Clothing category generates the highest revenue and sales

Accessories and Footwear follow next

Category ranking by frequency_of_purchases provides clear insight into customer preferences

⭐ 3. Demographic Behavior

Young Adults and Middle-aged customers are the top spenders

Gender filter allows exploring male vs female purchasing habits

⭐ 4. Seasonal Behavior

Treemap displays purchase distribution across:
Fall, Winter, Spring, and Summer
showing how different seasons impact buying frequency and revenue.

⭐ 5. Shipping Insights

Filters include:

2-Day Shipping

Express

Free Shipping

Next Day Air

Standard

Store Pickup

## 🛠️ Tech Stack
Tool	Purpose
Python	Data cleaning, transformation
Pandas / NumPy	Data wrangling
SQL	Customer segmentation, aggregations
Excel	Initial exploration
Power BI	Dashboard creation, modeling, visualizations
DAX	KPIs, dynamic measures
📂 Dataset Features

The dataset includes customer demographics, purchase history, category details, and behavioral variables:

age, age_group

category, item_purchased

purchase_amount

frequency_of_purchases

discount_applied

season

payment_method

subscription_status

gender

location

review_rating

shipping_type

## 📐 Data Modeling in Power BI

Star schema created with fact_purchase and dimension tables

Relationship modeling ensures smooth slicer interactions

DAX measures used for KPIs:

Number of Customers = DISTINCTCOUNT(customer[customer_id])

Average Purchase Amount = AVERAGE(customer[purchase_amount])

Average Review Rating = AVERAGE(customer[review_rating])

Total Revenue = SUM(customer[purchase_amount])

## 📊 Dashboard Features
✔ Interactive Slicers

Subscription status

Gender

Category

Shipping type

✔ KPIs

Customer count

Avg purchase amount

Avg review rating

✔ Visuals Included

Donut Chart

Treemap

Clustered Bar Charts

Horizontal Bar Charts

KPI Cards

Category ranking chart

Season-wise Treemap

## 🚀 Conclusion

This dashboard empowers businesses to understand customer behavior at every level—demographics, products, seasons, and purchasing habits.
It is ideal for retail analytics, marketing insights, and decision-making.
