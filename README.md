# 📊 AtliQ Hardware Excel Project

## 📌 Project Description
This project analyzes customer and market performance data for **AtliQ Hardwares** (2019-2021). It provides insights into **sales trends, customer growth, and revenue distribution** across different stores and platforms.

---

## 🔍 Sales Analysis
**Objective:**
- Tracks **year-over-year (YoY) net sales per customer**.
- Highlights **% growth (2021 vs. 2020)** to assess performance.
- Identifies **top-growing and declining customers**.

📌 **Business Impact:**  
Optimizes sales strategy by focusing on high-value customers, re-engaging declining ones, tailoring marketing efforts, and forecasting sales trends for better pricing.

---

## 💰 Finance Analysis
**Objective:**
- Tracks **YoY market sales** and **% achievement vs. target**.
- Identifies **high-performing vs. underperforming markets**.
- Highlights **sales trends** for strategic planning.

📌 **Business Impact:**  
Helps allocate resources to high-growth markets, improve weak ones, refine sales targets, predict market trends, and optimize expansion plans.

---

## 📈 P&L Market Analysis
**Objective:**
- Tracks **sales, costs, and profitability** across different markets.
- Highlights **gross margin %** to identify high/low-profit markets.
- Helps **optimize pricing and cost strategies**.

📌 **Business Impact:**  
Focuses on **profit optimization** by prioritizing high-margin markets, reducing costs, adjusting pricing strategies, and investing in high-performing markets.

---

## 🚀 Key Features

✅ **Sales Growth Analysis** - Compares yearly revenue changes and trends.  
✅ **Top Customer Insights** - Identifies high-revenue customers like Amazon & Flipkart.  
✅ **Market Trends** - Highlights growing and declining customer segments.  
✅ **Excel Analytics** - Used **formulas, pivot tables, and charts** to drive insights.  
✅ **SQL Queries** - Ready-to-use SQL scripts for deeper data exploration.  

---

## 🛠 Installation  

### 📥 Clone the Repository  
To install this project, run:  

```sh
git clone https://github.com/swaroopsamuel/AtliQ-Hardware-Excel-/tree/main
```

### 📂 Dataset  
This project includes sales data for analysis. Download the dataset:  

📌 [Customer Data (CSV)](https://github.com/swaroopsamuel/AtliQ-Hardware-Excel-/blob/main/dim_customer.csv)  
📌 [Market Data (CSV)](https://github.com/swaroopsamuel/AtliQ-Hardware-Excel-/blob/main/dim_market.csv)  
📌 [Products Data (CSV)](https://github.com/swaroopsamuel/AtliQ-Hardware-Excel-/blob/main/dim_product.csv)  
📌 [Fact Sales Monthly (CSV)](https://github.com/swaroopsamuel/AtliQ-Hardware-Excel-/blob/main/fact_sales_monthly.csv.gz)  

---

## 📊 Data Analysis Approach  

🔹 *Performed analysis using Excel*, leveraging **formulas and pivot tables** for insights.  

### 📌 Excel Formulas & Methods Used  
✔ **SUM()** – Aggregated total net sales and costs.  
✔ **Division & Subtraction** – Calculated percentage growth and profit margins.  
✔ **Pivot Tables** – Summarized and analyzed market-wise performance trends.  

🔹 *Generated insights for business stakeholders* to optimize sales and profitability.  

---

## 🔑 Key Insights  

✅ **Amazon led net sales in 2021** with **$82.1M**, marking a **218.9% YoY growth**, making it the most valuable customer. AtliQ Exclusive followed with **$61.1M**, securing the second-highest revenue.  

✅ **Key Growth Drivers:** Bulk orders, stronger partnerships, increased demand, or strategic pricing shifts.  

✅ **Customer Retention:** Steady sales growth across customers suggests **strong retention** and **potential for expanding premium offerings**.  

✅ **Regional Performance:**  
- **India ($161.3M)** and **USA ($87.8M)** led in total sales.  
- However, **target gaps (-$9.6M, -$10.2M)** highlight areas for **sales strategy enhancement**.  

✅ **Revenue Growth:**  
- **Net sales soared from $87.5M (2019) to $598.9M (2021)**.  
- This reflects a **204.5% increase**, showcasing **robust business expansion**.  

✅ **Margin Concerns:** Despite rising sales, **gross margin % dropped (-2.3%)**, signaling a **need for cost optimization and pricing adjustments**.  

## 🚀 Usage  

1️⃣ **Open the Power BI dashboard**:  
   - `Customer_Performance.pbix`  
   - `Market_Performance.pbix`  

2️⃣ **Apply filters** to analyze:  
   - **Customer sales trends**  
   - **Market performance**  
   - **Profitability insights**  

3️⃣ **Use SQL queries to extract key insights:**  

### 🔍 Retrieve the top 5 markets by net sales
```sql
SELECT market, SUM(net_sales) AS total_sales 
FROM market_performance 
GROUP BY market 
ORDER BY total_sales DESC 
LIMIT 5;
```


## 📩 Contact & Contributions
If you'd like to contribute, have questions, or need further insights, feel free to connect!

🔗 GitHub Profile: https://github.com/swaroopsamuel

📧 Email: swaroopn80@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/swaroopnakka/
