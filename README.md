# AdventureWorks Sales & Profit Analysis Dashboard (Power BI)

> **Author:** Swetha Julakanti  
> **Project Type:** Business Intelligence & Sales Analytics  
> **Tools Used:** Power BI, DAX, Power Query, Geo Maps, AdventureWorks Dataset

---

## 📌 Project Overview

This project showcases an end-to-end sales and profitability analysis using the AdventureWorks dataset. The dashboard enables users to explore regional sales performance, product-level profitability, return rates, and customer behavior across time.

Key features include KPI cards, dynamic filtering, trend analysis, and geographic visualizations.

---

## 🧰 Tools and Technologies

- Power BI Desktop  
- Power Query for data transformation  
- DAX for KPIs and measures  
- Bing Maps visualization  
- Slicers, buttons, and bookmarks for interactivity

---

## 📊 Dataset Overview

The data was derived from the AdventureWorks dataset and includes:
- Order details by product and region
- Revenue, profit, and return quantities
- Product categories and return rates
- Customer income and occupation segments
- Geographical sales distribution

---

## 🖥️ Dashboard Features

### 1. Executive KPI Summary  
- 📈 **Total Revenue**: $25M  
- 💰 **Total Profit**: $10M  
- 📦 **Total Orders**: 25K  
- 🔁 **Return Rate**: 2.17%


### 2. Sales Trends and Category Breakdown  
- Monthly revenue growth with trendline  
- Orders by category: Accessories, Bikes, Clothing  
- Top 10 Products with revenue and return rate  
- Most ordered and most returned product types
<img width="700" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/effb17f7-37f5-4ac4-bea8-cf6c057b3d99" />


### 3. Regional Performance Map  
- Sales volume visualized across **North America**, **Europe**, **Pacific**  
- Region filter using dynamic buttons
<img width="700" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/6e620da2-28f2-4be9-8c6e-04009407434d" />


### 4. Product Drill-down Page  
- Product-level metrics: revenue, profit, returns  
- Monthly target comparisons  
- Weekly returns and user-driven price simulation
<img width="700" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/f63d502e-91d3-4acd-8bc4-adfa392d3a72" />


### 5. Customer Insights  
- Customer breakdown by income and occupation  
- Top 100 customers by revenue and orders  
- Year filter and growth trend in customer base
<img width="700" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/7211054a-dc97-4d73-9b67-cdab3ed71d0a" />
<img width="700" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/96ca9549-7956-4694-a3e2-2eed286ac48f" />
<img width="700" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/8843cfdc-f88a-4c4b-a659-2e839ea80456" />

---

## 💡 Key Insights

- **Tires and Tubes** are the most ordered product type  
- **Shorts** are the most returned product  
- **Accessories** drive the highest number of orders  
- **Europe and North America** are top-performing regions  
- Return rate remains low (~2.2%) despite volume  
- **Revenue is steadily increasing** over time with minor dips

---

## 🧠 Lessons Learned

- Geo-mapping in Power BI enhances global trend interpretation  
- DAX was essential for return rate and adjusted profit simulations  
- Button-based filtering improves report usability  

---

## 📂 Repository Structure

```bash
📦 AdventureWorks_Sales_Profit_Dashboard
├── README.md
├── AdventureWorks_Dashboard.pbix
├── datasets/
│   └── adventureworks_sales_sample.csv
├── screenshots/
│   ├── sales_overview_kpis.png
│   ├── region_map.png
│   ├── product_analysis.png
│   ├── customer_insights.png
│   └── return_trends.png
