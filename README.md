# Sales Analysis Project

This project focuses on analyzing sales data to uncover key business insights using **SQL**, **Python**, and **Power BI**. The goal is to track revenue, profit, and costs while visualizing sales trends to inform business decisions.

---

## Project Overview

The Sales Analysis project performs:

1. **Revenue and Cost Calculation**  
   - **Total Revenue**: Sum of all sales orders  
   - **Total Cost**: `Order Quantity * Total Unit Cost`  
   - **Profit**: `Total Revenue - Total Cost`  
   - **Profit Margin %**: `(Profit / Revenue) * 100`

2. **Exploratory Data Analysis (EDA)**  
   - Analyze sales trends over time  
   - Detect seasonality and spikes in sales  
   - Identify monthly and yearly revenue patterns  
   - Detect outliers in revenue and profit  

3. **Dashboard Design**  
   - Designed interactive dashboards in Power BI  
   - Features include KPIs like Total Revenue, Total Profit, Profit Margin %, Number of Orders, and Revenue per Order  
   - Multiple pages for insights: Overview, Product/Channel Performance, Geographic Insights, and Q&A

---

## Tools & Technologies

- **SQL**: For data extraction and calculations  
- **Python (Pandas & Matplotlib)**: For data preprocessing and monthly sales trend visualization  
- **Power BI**: For interactive dashboards  
- **Excel/CSV**: Data source and pre-processing  

---

## Dataset

The dataset includes:

- Order ID, Order Date  
- Product and Category information  
- Customer and regional information  
- Quantity, Unit Cost, Total Revenue  

> *Note: This dataset is anonymized/sample data for analytical purposes.*

---

## Power BI Dashboard

Visual representation of key insights:

### Overview Page
![Dashboard 1](images/dashboard1.png)

### Product/Channel Performance
![Dashboard 2](images/dashboard4.png)

### Geographic Insights / Q&A
![Dashboard 3](images/dashboard5.png)

**Features:**

- Interactive charts to explore trends  
- Filter by month, region, or product category  
- Highlight top-performing products and regions  
- KPIs displayed in summary boxes  

---

## Insights & Findings

- Peak sales months: **January, October**  
- Total revenue consistently between **23M–26M**  
- Outliers detected during **January** (lower spike) and **July** (higher spike)  
- Key KPIs: Total Revenue, Total Profit, Profit Margin %, Number of Orders, Revenue per Order  

---

## How to Run

1. Open `Sales_Analysis.sql` in your SQL environment to calculate revenue, cost, and profit.  
2. Use `Sales_Analysis.ipynb` to explore EDA and plot monthly trends.  
3. Open `Sales_Analysis.pbix` in Power BI to view interactive dashboards.  

---

## Contact

For questions or feedback, reach out at **[yash127pandey@gmail.com]**  

