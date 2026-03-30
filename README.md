# Exploratory Data Analysis on Electronics E-commerce Dataset (SQL)
📦 Dataset: 500+ Products | 🛒 Domain: E-commerce | 🧠 Technique: SQL-based EDA

## 📊 Project Summary
Performed end-to-end exploratory data analysis (EDA) on an electronics e-commerce dataset using SQL. Cleaned and transformed raw data, engineered analytical features, and applied statistical techniques to uncover insights on pricing, discounts, and customer engagement across 500+ products and 20+ categories.


## 🔍 Project Overview
The dataset consists of 500+ electronics products across 20+ sub-categories, containing pricing, discount, rating, and review information.
This project performs end-to-end Exploratory Data Analysis (EDA) on an electronics e-commerce dataset using MySQL.
The objective was to clean raw product data, engineer analytical features, and derive statistical insights related to pricing structure and customer engagement patterns.

## 📈 Key Insights
- Product prices are right-skewed, with most items in the mid-range and a few premium products driving higher price extremes  
- Discounts vary across categories, indicating different pricing and promotional strategies  
- Weak correlation (~0.13) between ratings and reviews shows that popularity does not necessarily reflect customer satisfaction  
- Some lower-priced products achieve high ratings, highlighting strong value-for-money opportunities  


## 🎯 Business Value
- Helps businesses optimize pricing and discount strategies based on category-level performance  
- Enables identification of high-performing products and value-for-money offerings  
- Supports data-driven decision-making for improving customer engagement and sales  
- Highlights inconsistencies in pricing, helping standardize strategies across brands and categories  



## Tools & Technologies
MySQL
SQL Window Functions
Regular Expressions (REGEXP)
Statistical Analysis (Covariance, Correlation, Regression)
IQR-Based Outlier Detection

## ⚙️ Key Steps Performed
### 1️⃣ Data Ingestion
Bulk-loaded dataset using LOAD DATA INFILE
Performed schema validation and datatype normalization

### 2️⃣ Data Cleaning & Feature Engineering
Cleaned and standardized price values (handled ranges using midpoint logic)
Reconstructed MRP using discount logic
Standardized discount categories
Extracted numeric rating and review counts using REGEXP
Derived brand names using string parsing
Removed unnecessary columns and optimized schema

### 3️⃣ Statistical & Analytical Techniques

Percentile analysis using PERCENT_RANK()
IQR-based outlier detection
Computed covariance and correlation (Rating vs Reviews → 0.13)
Estimated linear regression slope (Price vs MRP)
Conducted segment-level grouped statistical summaries



## 🚀 Skills Demonstrated

- Advanced SQL  
- Window Functions  
- Data Cleaning & Feature Engineering  
- Statistical Thinking  
- Analytical Interpretation  
- Structured Problem Solving  
