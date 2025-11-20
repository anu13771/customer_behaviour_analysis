<div align="center">

# 🛒 **Customer Behavior Analysis**  
### **SQL • Python • Power BI**

A complete end-to-end data analysis project exploring customer purchasing patterns, product ratings, and behavioral insights using real-world data.

---

### 🔗 **Project Files**
📌 **SQL Queries:** `customer_behavior_sql_queries.sql`  
📌 **Power BI Dashboard:** `customer_behavior_dashboard.pbix`  
📌 **Python Notebook:** `customer_behavior_analysis.ipynb`

</div>

---

## 🚀 **1. Project Overview**

This project uncovers customer insights such as:

- ⭐ **Top-rated products**
- 🛍️ **Most purchased items**
- 👥 **Customer segmentation**
- 📅 **Monthly buying trends**
- 📦 **Sales distribution**
- 🧹 **Data cleaning & preprocessing**

Data was processed using **PostgreSQL**, analyzed in **Python**, and visualized through a fully interactive **Power BI Dashboard**.

---

## 🗄️ **2. SQL Analysis (PostgreSQL)**

All SQL queries are available here:  
👉 **`customer_behavior_sql_queries.sql`**

### 🔹 Example Query — Top 5 Highest Rated Products:
```sql
SELECT item_purchased,
       ROUND(AVG(review_rating)::numeric, 2) AS avg_rating
FROM customer
GROUP BY item_purchased
ORDER BY avg_rating DESC
LIMIT 5;


🐍 3. Python Analysis (Jupyter Notebook)

Python was used for:

📥 Pulling data from PostgreSQL

🧼 Cleaning & preprocessing

📊 Exploratory Data Analysis (EDA)

📈 Visualizing customer behavior

🔹 Example Python Code
import pandas as pd
import psycopg2
import matplotlib.pyplot as plt

# Connect to PostgreSQL
conn = psycopg2.connect(
    host="localhost",
    database="customer_behaviour",
    user="postgres",
    password="your_password"
)

# Load data
df = pd.read_sql("SELECT * FROM customer;", conn)

# Display sample
print(df.head())

# Plot average rating per product
avg_rating = df.groupby("item_purchased")["review_rating"].mean()
avg_rating.plot(kind="bar", figsize=(10,5))

plt.title("Average Rating by Product")
plt.xlabel("Product")
plt.ylabel("Rating")
plt.show()

📊 4. Power BI Dashboard

The interactive dashboard is included:

👉 customer_behavior_dashboard.pbix

Dashboard Includes:

⭐ KPI Summary

📦 Top Products

⭐ Average Rating Analysis

📅 Time-Based Trends

👥 Customer Segmentation

🎛️ Filters & Slicers for Exploration

🛠 5. Technologies Used
Technology	Purpose
PostgreSQL	Database & SQL analysis
Python	Data cleaning & EDA
Pandas	Data manipulation
Matplotlib	Visualizations
Power BI	Dashboard & insights
Jupyter Notebook	Interactive exploration
GitHub	Version control
▶️ 6. How to Run This Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/your-repo-name.git

2️⃣ Run SQL Queries

Open PostgreSQL and execute:

customer_behavior_sql_queries.sql

3️⃣ Run the Python Notebook

Open:

customer_behavior_analysis.ipynb

4️⃣ Open the Power BI Dashboard

Double-click:

customer_behavior_dashboard.pbix

🔍 7. Key Insights

✔ Products with consistently high ratings
✔ Strong correlation between categories & ratings
✔ Clear monthly seasonality in purchases
✔ Top 10 customers drive major sales
✔ Customer preferences visible through item patterns

<div align="center">
👩‍💻 Author
Anushka Gupta

Data Analyst • SQL • Python • Power BI

</div>
