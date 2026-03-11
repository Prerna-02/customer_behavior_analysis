# Customer Behavior Analysis

An end-to-end data analytics project that explores customer shopping behavior using **Python, PostgreSQL, and Power BI**. The project covers data cleaning, feature engineering, SQL-based business analysis, and interactive dashboarding to uncover patterns in customer spending, subscriptions, product preferences, and sales performance.

## 📌 Project Overview

The dataset contains **3,900 customer purchase records** across multiple product categories and customer attributes. The objective of this project is to transform raw transactional data into actionable business insights that can support marketing, loyalty, pricing, and product decisions.

## 🎯 Objectives

* Clean and preprocess raw shopping behavior data using Python
* Perform feature engineering to improve analysis readiness
* Load the transformed dataset into PostgreSQL for structured querying
* Answer business questions using SQL
* Build an interactive Power BI dashboard for decision-making

## 📊 Dataset Summary

* **Rows:** 3,900
* **Columns:** 18
* **Key attributes:** age, gender, category, item purchased, purchase amount, subscription status, shipping type, review rating, discounts, and purchase frequency
* **Missing values handled:** 37 null values in `review_rating`

## 🛠️ Tools & Technologies

* **Python** - data cleaning, preprocessing, feature engineering
* **Pandas / Jupyter Notebook** - exploratory analysis and transformation
* **PostgreSQL** - business query analysis
* **Power BI** - dashboard creation and data visualization

## 🔄 Workflow

1. **Data Cleaning in Python**

   * Checked data types, summary statistics, and null values
   * Imputed missing `review_rating` values using category-wise median
   * Standardized column names into snake_case
   * Removed redundant fields

2. **Feature Engineering**

   * Created `age_group`
   * Created `purchase_frequency_days`

3. **Database Integration**

   * Connected Jupyter Notebook with PostgreSQL
   * Loaded the cleaned dataset into PostgreSQL for SQL analysis

4. **Business Analysis with SQL**

   * Revenue by gender
   * High-spending discount users
   * Top-rated products
   * Shipping type comparison
   * Subscriber vs non-subscriber revenue analysis
   * Discount-dependent products
   * Customer segmentation
   * Top products by category
   * Repeat buyers and subscriptions
   * Revenue by age group

5. **Dashboarding in Power BI**

   * Built an interactive dashboard with filters for subscription status, gender, category, and shipping type
   * Visualized customer count, average purchase amount, review rating, revenue by category, sales by category, and age-group-wise performance

## 🔍 Key Insights

* Non-subscribers made up the majority of customers and contributed higher total revenue overall.
* Clothing generated the highest revenue and sales among product categories.
* Young adults contributed the highest revenue among age groups.
* Express shipping users showed slightly higher average purchase amounts than standard shipping users.
* Loyal customers formed the largest customer segment, indicating strong repeat purchase behavior.

## 💡 Business Recommendations

* Strengthen subscription benefits to improve subscriber conversion
* Build loyalty programs for repeat buyers
* Reassess discount-heavy products to protect margins
* Promote top-rated and best-selling products more aggressively
* Run targeted campaigns for high-revenue age groups and shipping preferences


## Conclusion

This project demonstrates a complete analytics pipeline — from raw data preparation to database-driven analysis and dashboard storytelling. It highlights how Python, PostgreSQL, and Power BI can be combined to turn customer transaction data into practical business insights.

---

⭐ If you found this project useful, consider giving the repository a star.

