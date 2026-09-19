# Customer Shopping Behaviour Analysis

An end-to-end data analytics project focused on understanding customer shopping behaviour, purchasing patterns, product performance, revenue, and subscription trends using Python, SQL, and Power BI.

## 📌 Project Overview

This project analyzes **3,900 customer purchase records across 18 columns** to uncover meaningful patterns in customer behaviour and purchasing activity.

The project follows an end-to-end analytics workflow:

**Python → SQL → Power BI**

Python was used for data cleaning and preparation, SQL for business-focused analysis, and Power BI for interactive data visualization.

## 🎯 Objectives

- Analyze customer purchasing behaviour
- Identify revenue and spending patterns
- Understand subscription behaviour
- Analyze product performance and customer ratings
- Examine discount and shipping patterns
- Segment customers based on purchase history
- Present key insights through an interactive Power BI dashboard

## 🛠️ Tools & Technologies

- **Python** – Data cleaning, preparation & feature engineering
- **Pandas** – Data manipulation and analysis
- **SQL** – Business analysis and querying
- **MySQL** – Database analysis
- **Power BI** – Interactive dashboard and data visualization

## 📊 Dataset

The dataset contains **3,900 rows and 18 columns**.

### Key Features

- Customer demographics
- Purchase details
- Product categories
- Purchase amount
- Subscription status
- Discount and promotional activity
- Previous purchases
- Purchase frequency
- Review ratings
- Shipping type
- Season, size, and color

There were **37 missing values in the Review Rating column**, which were handled during the data-cleaning stage.

## 🧹 Data Cleaning & Preparation

Python was used to prepare the dataset for analysis.

Key steps included:

- Loading the dataset using Pandas
- Exploring the dataset using `info()` and `describe()`
- Checking and handling missing values
- Imputing missing review ratings using the median rating of each product category
- Standardizing column names using snake_case
- Creating an `age_group` feature
- Creating a `purchase_frequency_days` feature
- Checking data consistency between discount and promotional fields
- Removing the redundant `promo_code_used` column
- Loading the cleaned dataset into the database for SQL analysis

## 🔎 SQL Analysis

SQL was used to answer key business questions, including:

1. Revenue by gender
2. High-spending customers who used discounts
3. Top 5 products by average review rating
4. Comparison of Standard vs. Express shipping
5. Subscribers vs. non-subscribers
6. Products with the highest percentage of discounted purchases
7. Customer segmentation based on purchase history
8. Top 3 products within each category
9. Relationship between repeat purchases and subscriptions
10. Revenue contribution by age group

## 📈 Power BI Dashboard

The cleaned and analyzed data was visualized using Power BI through an interactive dashboard.

The dashboard focuses on:

- Customer behaviour
- Revenue patterns
- Product performance
- Subscription analysis
- Purchasing patterns
- Customer demographics

## 💡 Business Recommendations

Based on the analysis, the project provides recommendations related to:

- **Subscription Growth** – Promote exclusive benefits for subscribers
- **Customer Loyalty** – Encourage repeat customers through loyalty programs
- **Discount Strategy** – Review discount policies while considering profitability
- **Product Positioning** – Highlight top-rated and best-performing products
- **Targeted Marketing** – Focus on high-revenue customer groups

## 🔄 Project Workflow

```text
Raw Customer Data
        ↓
Python Data Cleaning & Preparation
        ↓
Feature Engineering
        ↓
Database Integration
        ↓
SQL Business Analysis
        ↓
Power BI Dashboard
        ↓
Insights & Recommendations
