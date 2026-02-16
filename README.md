# Exploratory Data Analysis on Electronics E-commerce Dataset (SQL)
## 🔍 Project Overview

This project performs end-to-end Exploratory Data Analysis (EDA) on an electronics e-commerce dataset using MySQL.
The objective was to clean raw product data, engineer analytical features, and derive statistical insights related to pricing structure and customer engagement patterns.

The dataset consists of 500+ electronics products across 20+ sub-categories, containing pricing, discount, rating, and review information.

# Tools & Technologies

MySQL

SQL Window Functions

Regular Expressions (REGEXP)

Statistical Analysis (Covariance, Correlation, Regression)

IQR-Based Outlier Detection

# ⚙️ Key Steps Performed
# 1️⃣ Data Ingestion

Bulk-loaded dataset using LOAD DATA INFILE

Performed schema validation and datatype normalization

# 2️⃣ Data Cleaning & Feature Engineering

Cleaned and standardized price values (handled ranges using midpoint logic)

Reconstructed MRP using discount logic

Standardized discount categories

Extracted numeric rating and review counts using REGEXP

Derived brand names using string parsing

Removed unnecessary columns and optimized schema

# 3️⃣ Statistical & Analytical Techniques

Percentile analysis using PERCENT_RANK()

IQR-based outlier detection

Computed covariance and correlation (Rating vs Reviews → 0.13)

Estimated linear regression slope (Price vs MRP)

Conducted segment-level grouped statistical summaries

# 📈 Key Insights

Weak positive correlation (0.13) between product rating and review count — popularity does not necessarily imply higher satisfaction.

Price distribution is positively skewed, with high-end products contributing to upper outliers.

# 🎯 Business Value

This project demonstrates:

Ability to transform raw e-commerce data into structured analytical features

Application of statistical reasoning using SQL

Segment-level performance evaluation

Practical implementation of regression and correlation concepts

# 🚀 Skills Demonstrated

Advanced SQL

Window Functions

Data Cleaning & Feature Engineering

Statistical Thinking

Analytical Interpretation

Structured Problem Solving

Certain sub-categories demonstrate stronger alignment between engagement and ratings.

Brand-level analysis reveals pricing consistency variations across segments.
