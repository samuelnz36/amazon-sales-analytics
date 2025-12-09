# Amazon Sales Analytics
### A Data Engineering & Analytics Project using SQL, Python, and Power BI  
Created by: Samuel N C

## Project Overview
This project analyzes Amazon-style e-commerce sales data (India–focused) to uncover insights about revenue, orders, returns, customer behavior, and performance across product categories and states.

The goal is simple:
- Clean the dataset  
- Explore meaningful patterns through Python  
- Run structured analysis using SQL  
- Build a professional Power BI dashboard

This project demonstrates practical skills in data preprocessing, exploratory analysis, SQL querying, and dashboard creation.

---

## 1. Data Cleaning (Notebook: 01_data_cleaning.ipynb)
Key steps performed:
- Removed missing or invalid values  
- Standardized column names and data types  
- Converted date columns to proper datetime formats  
- Derived additional fields such as Month_Name, Year, Returned flag  
- Validated numerical fields like revenue and quantities  

After cleaning, a final structured `sales` table was ready for SQL and EDA.

---

## 2. Exploratory Data Analysis (Notebook: 02_eda.ipynb)
Major KPIs calculated:

Total Revenue: ~₹1.11B  
Total Orders: 15,000  
Total Units Sold: 44,770  
Average Order Value: ₹74,544  
Average Rating: 3.04  
Return Rate: 32.5%  
Unique Customers: 7,259  
States Covered: 28  

### Key EDA Visuals
- Daily revenue trend  
- Monthly revenue breakdown  
- Category-level revenue  
- Payment method distribution  
- Rating distribution  
- Return behavior analysis  
- State-level revenue and return rates  

---

## 3. SQL Analysis (Notebook: 03_sql_queries.ipynb)
A SQLite database (sales.db) was created to run SQL queries for deeper insights.

### Important SQL results:

Top Categories by Revenue:
- Beauty  
- Electronics  
- Books  
- Clothing  
- Home & Kitchen  

Most Returned Categories:
- Books  
- Electronics  
- Clothing  

Return Rate by Payment Method:
- Credit Card: 33.34%  
- Debit Card: 32.70%  
- UPI: 32.11%  
- Cash on Delivery: 31.98%  

Daily Revenue:
A full time-series query showing revenue per day.

State-Level Revenue Ranking:
Highest revenues from Sikkim, Rajasthan, Chhattisgarh, Meghalaya, Tamil Nadu, etc.

---

## 4. Power BI Dashboard

### Page 1 — Overall Sales Overview
Includes:
- Total Revenue  
- Total Orders  
- Total Units Sold  
- AOV  
- Average Rating  
- Return Rate  
- Monthly Revenue Trend  
- Revenue by Product Category  
- Payment Method Distribution  
- Delivery Status Breakdown  

### Page 2 — Product Deep Dive
Includes:
- Top 10 Products by Revenue  
- Top 10 Most Returned Products  
- Return Rate by Category  
- Average Rating by Category  
- Units Sold by Category  

### Page 3 — State-Level Analysis
Includes:
- India map showing revenue by state  
- Return Rate by State  
- Average Rating by State  
- Rating Distribution  
- Return Rate by Payment Method  

---

## Project Structure

Amazon-Sales-Analytics/
│
├── data/
│   └── sales.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_sql_queries.ipynb
│
├── database/
│   └── sales.db
│
├── powerbi/
│   └── Amazon_Sales_Analytics.pbix
│
└── README.md

---

## Final Insights

- Beauty, Electronics, and Books drive the highest revenue.  
- Return rates remain consistently high (~32%) across categories and states.  
- Ratings do not strongly correlate with returns.  
- Payment methods show nearly identical return behavior.  
- High-revenue states include Sikkim, Rajasthan, and Chhattisgarh.  
- Customer ratings are fairly normally distributed across 1–5.

---

## Skills Demonstrated
- Python (Pandas, Matplotlib, Seaborn)  
- SQL (SQLite, analytical queries)  
- Data Cleaning & Transformation  
- Exploratory Data Analysis  
- Power BI Dashboarding  
- Data Storytelling  

---

## Author
Samuel N C
