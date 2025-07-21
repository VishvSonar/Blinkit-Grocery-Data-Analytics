# Blinkit Data Analysis Project 🛒📊

This project involves a comprehensive analysis of Blinkit's sales and outlet data using **SQL** and **Power BI**. The goal is to derive insights on sales trends, product categories, and outlet performance to support data-driven decision-making.

---

## 📁 Dataset

The dataset contains transaction-level sales data from Blinkit, including:
- Item types and their categories
- Outlet establishment years and locations
- Sales figures, MRP, visibility
- Other related attributes

---

## 🛠 Tools & Technologies

- **SQL**: For querying and data exploration
- **Power BI**: For creating interactive dashboards
- **Excel**: For initial data formatting

---

## 📌 Key Analysis Performed

- Total sales in millions by outlet establishment year
- Average sales across outlets
- Top performing product categories
- Sales trends over different outlet years
- Number of items and outlet count distribution

---

## 📈 Dashboard (Power BI)

The Power BI dashboard provides a visual summary of key insights:
- Sales KPIs
- Category-wise performance
- Outlet year-wise analysis
- Filterable and interactive visuals

📎 **Dashboard Screenshot**:  
![Blinkit Dashboard](./Blinkit_Dashboard.png)

---

## 🧾 SQL Report Highlights

Sample SQL queries used in this analysis:

```sql
SELECT CAST(SUM(Sales)/ 1000000 AS DECIMAL(10,2)) AS Sales_Millions
FROM Blinkit_Data
WHERE Outlet_Establishment_Year = 2022;
