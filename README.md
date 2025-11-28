### **🛒 Customer Shopping Behavior Analysis**
End-to-End Data Analytics Project using Python, SQL & Power BI

This project delivers a complete analytical workflow — from raw data exploration to business intelligence dashboarding — to uncover key patterns in customer purchasing behavior, product performance, discount usage, and revenue drivers.
It is designed as a real-world, industry-grade analytics case study suitable for portfolio presentation, academic submissions, and interview discussions.

<img width="1373" height="737" alt="image" src="https://github.com/user-attachments/assets/36940b30-a59a-42e8-9e41-d131c138809c" />

---

### **🚀 Project Highlights**

- Performed data cleaning, imputation, and feature engineering in Python
- Designed a relational database pipeline using PostgreSQL
- Executed deep-dive SQL analysis to derive business insights
- Developed a Power BI dashboard for interactive visualization
- Generated strategic recommendations for data-driven decision-making

---

### **📂 Project Assets**

File	Description : 
- customer_behavior_analysis.ipynb	Python EDA & preprocessing notebook
- customer_behavior_sql_queries.sql	Insights-driven SQL query collection
- customer_behavior_dashboard.pbix	Interactive Power BI dashboard
- Customer-Shopping-Behavior-Analysis.pptx	Presentation summarizing findings

--- 

### **📊 Dataset Overview**

Rows: 3,900

Columns: 18

Domain: Retail / E-commerce

Missing Values: 37 (in review_rating)

Key Data Dimensions

Customer demographics

Product category & attributes

Purchase amounts, discounts & shipping type

Behavioral indicators (previous purchases, frequency)

Ratings & reviews

---

### **🐍 Python: Data Preparation & Feature Engineering**

✔ Data Cleaning

Standardized all column names to snake_case

Converted datatypes and handled inconsistent formats

✔ Missing Value Treatment

Imputed missing review_rating values using category-wise median

✔ Feature Engineering

Created age_group buckets

Derived purchase_frequency_days

Encoded categorical variables for modeling & SQL compatibility

✔ Database Integration

Exported cleaned dataset into PostgreSQL for analytical querying

---

### **🛢️ SQL Analysis: Key Insights**

💰 Revenue Contribution by Gender

Male: $157,890

Female: $75,191

⭐ Top-Rated Products
Rank	Product	Avg Rating
1	Gloves	3.86
2	Sandals	3.84
3	Boots	3.82
4	Hat	3.80
5	Skirt	3.78
🚚 Customer Spend by Shipping Type
Shipping Type	Avg Spend
Express	$60.48
Standard	$58.46
📦 Subscribers vs Non-Subscribers
Group	Count	Avg Spend
Subscribers	1053	$59.49
Non-Subscribers	2847	$59.87
🏷️ Discount-Dependent Products

Products with the highest proportion of discounted purchases:

Hat (50%)

Sneakers (49.66%)

Coat (49.07%)

Sweater (48.17%)

Pants (47.37%)

👥 Customer Segmentation
Segment	Count
Loyal	3,116
Returning	701
New	83
💸 Revenue by Age Group
Age Group	Revenue
Young Adult	$62,143
Middle-Aged	$59,197
Adult	$55,978
Senior	$55,763
📊 Power BI Dashboard

An interactive dashboard showcasing:

Revenue trends

Product performance

Customer segmentation

Shipping preferences

Discount behavior

Rating distributions

The dashboard is designed for executive-level decision-making with clean KPIs and drill-down capabilities.

💼 Business Recommendations
1. Strengthen Loyalty & Retention

Introduce rewards, tiered benefits, and exclusive access for repeat customers

2. Optimize Discount Strategy

Reduce discounts on high-demand items like hats, sneakers & coats

Use personalized promotions instead of blanket discounts

3. Boost Subscription Adoption

Offer free shipping or early access to products for subscribers

4. Promote High-Rated Products

Highlight gloves, sandals, boots & hats in campaigns

Bundle complementary products for upselling

5. Target High-Revenue Segments

Focus marketing on Young Adults and Express-shipping users

🧰 Tech Stack

Python: Pandas, NumPy, Matplotlib

SQL: PostgreSQL

Business Intelligence: Power BI

Versioning & Docs: GitHub, Markdown


