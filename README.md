# Customer-Shopping-Behaviour
Customer Shopping Behavior Analysis using Python, SQL, and Power BI. Includes data cleaning with Pandas, EDA, SQL-based business insights, and an interactive dashboard to explore business data.

# 🛒 Customer Shopping Behavior Analysis

A complete end-to-end data analytics project exploring customer purchase patterns, spending behavior, demographics, and product performance using Python (Pandas), SQL, and Power BI.

This project demonstrates skills in data cleaning, EDA, SQL business analysis, and interactive dashboarding.

---

## 📌 Project Overview

This project analyzes customer shopping behavior using 3,900 transactions across several product categories.

The goal is to uncover:

- Category-wise sales  
- Gender-wise spending patterns  
- Age group purchasing trends  
- Discount vs. non-discount behavior  
- Subscription and loyalty patterns  

The final output includes a cleaned dataset, SQL insights, and a Power BI dashboard.

---

## 🗂 Dataset Summary

- Rows: 3,900  
- Columns: 18  

Contains:

- Customer Demographics  
  - Age  
  - Gender  
  - Location  
  - Subscription Status  

- Purchase Details  
  - Category  
  - Item Purchased  
  - Purchase Amount  
  - Season  
  - Size  
  - Color  

- Shopping Behavior  
  - Discounts  
  - Promo Code  
  - Frequency of Purchases  
  - Previous Purchases  
  - Review Ratings  
  - Shipping Type  

Missing Values:  
- 37 missing ratings (handled during cleaning)

---

## 🧹 Data Cleaning (Python – Pandas)

Key steps performed:

- Loaded and inspected the dataset using `info()` and `describe()`
- Handled missing values by imputing Review Rating using median rating per product category
- Standardized column names to snake_case
- Feature engineering:
  - Created age_group  
  - Created purchase_frequency_days  
- Dropped redundant features such as `promo_code_used`
- Loaded cleaned data into PostgreSQL for SQL analysis

---

## 📊 Exploratory Data Analysis (EDA)

Used Python (Pandas, Matplotlib, Seaborn) to analyze:

- Category-wise sales distribution
- Age group spending trends
- Gender-wise revenue contribution
- Impact of discounts on purchasing
- Subscription behavior
- Shipping type vs. purchase amount

---

## 🛢 SQL Business Analysis (PostgreSQL)

Performed structured analysis to answer 10 real-world business questions, including:

- Revenue contribution by gender  
- Identification of high-spending customers using discounts  
- Top 5 products by review rating  
- Standard vs. Express shipping comparison  
- Subscribers vs. Non-Subscribers: revenue and average spend  
- Products most dependent on discounts  
- Customer segmentation (New, Returning, Loyal)  
- Top 3 products per category  
- Repeat buyers and subscription likelihood  
- Revenue contribution by age group  

These SQL queries help build a strong business narrative.

---

## 📈 Power BI Dashboard

An interactive dashboard was developed to visualize:

- Category-wise sales  
- Gender-based performance  
- Age group purchasing trends  
- Discount usage  
- Subscriber vs. non-subscriber revenue  
- Review rating patterns  

---

## 💡 Business Recommendations

Based on insights, the following strategies are suggested:

- Improve subscription value and targeted marketing  
- Launch loyalty programs for repeat buyers  
- Optimize discount strategies  
- Promote high-rated and best-selling products  
- Target high-revenue age groups  
- Focus marketing on express-shipping users  

---
