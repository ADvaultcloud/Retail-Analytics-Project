# 🛒 Retail Analytics Project: Sales Forecasting & Market Basket Analysis

This project analyzes over 3 million grocery orders to uncover purchasing patterns and forecast future sales using a combination of **Python**, **SQL**, **Excel**, and **Power BI**. It simulates the work of a Data Analyst at a retail or CPG company aiming to improve inventory planning, marketing promotions, and product bundling strategies.

---
---
## 📌  Project Objectives

This project addresses multiple real-world business problems in retail operations and product strategy:

### 🎯 1. **Sales Forecasting**
> Predict future sales to improve stock planning and minimize overstock/stockouts.

- ✅ Used **Prophet (Python)** to model seasonality and trends in weekly sales.
- ✅ Forecasted demand per department and day-of-week using **Excel Forecast Sheet** and **Power BI analytics** pane.

### 🎯 2. **Market Basket Analysis**
> Identify product pairings frequently purchased together to improve cross-selling.

- ✅ Created binary transaction matrix using Pandas.
- ✅ Applied **Apriori algorithm** to find frequent itemsets.
- ✅ Generated association rules with lift and confidence metrics.
- ✅ Built a product affinity network in Power BI.

### 🎯 3. **Customer Purchase Behavior Analysis**
> Understand when and how often customers shop to improve personalized marketing.

- ✅ Analyzed reordering patterns and frequency using SQL.
- ✅ Identified high-value customers by average cart size and reorder rate.
- ✅ Segmented customers by time of purchase, loyalty, and volume.

### 🎯 4. **Product Performance Scoring**
> Evaluate product success based on reorder rates and sales contribution.

- ✅ Built KPIs like `Reorder Ratio`, `Avg Cart Position`, and `Sales % Contribution`.
- ✅ Identified underperforming SKUs for discount or phase-out strategies.
- ✅ Used Power BI cards and KPI visuals to rank products dynamically.

### 🎯 5. **Inventory Optimization**
> Help reduce carrying costs by aligning inventory with predicted demand.

- ✅ Merged forecast data with product availability and lead time info.
- ✅ Flagged SKUs at risk of overstock using variance between forecast and past sales.
- ✅ Created Power BI alerts for category managers to act proactively.

### 🎯 6. **Sales Trend Decomposition**
> Break down sales trends by product, time, and customer segment.

- ✅ Used DAX in Power BI to calculate YOY and MOM sales changes.
- ✅ Decomposed trends by day-of-week, time-of-day, and category.
- ✅ Created heatmaps and line charts to visualize patterns.

### 🎯 7. **Store Operational Insights**
> Understand peak order times and volume to optimize staffing and logistics.

- ✅ Analyzed hourly order patterns to identify peak shopping windows.
- ✅ Recommended staffing adjustments based on order surges.
- ✅ Integrated with a calendar view in Power BI for operations scheduling.

### 🎯 8. **Aisle and Department-Level Analysis**
> Provide category managers with data to track performance across aisles.

- ✅ Aggregated sales and reorder KPIs at the aisle and department level.
- ✅ Highlighted top- and bottom-performing departments.
- ✅ Delivered visual drill-down reports in Power BI with filters by time and product class.

### 🎯 9. **Outlier & Anomaly Detection**
> Identify unusual sales spikes or drops for quick investigation.

- ✅ Used statistical thresholds and Prophet model uncertainty intervals.
- ✅ Flagged anomalies in Power BI with conditional formatting.
- ✅ Suggested causes based on time, product, or customer segment.

### 🎯 10. **Business-Ready Executive Dashboard**
> Build a clean, interactive dashboard for stakeholders.

- ✅ Used **Power BI** to create slicers by department, weekday, and product.
- ✅ Visualized:
  - Time series trends
  - Sales forecasts
  - Association rules
  - Top-performing SKUs
- ✅ Included KPIs, tooltips, and drill-down interactivity

---

## 🗂️ Dataset

**Source:** [Instacart Market Basket Dataset on Kaggle](https://www.kaggle.com/datasets/instacart/market-basket-analysis)  
**Size:** ~3 million orders from 200k users across 50k+ products

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python (Pandas, Prophet, mlxtend)** | Data wrangling, forecasting, market basket modeling |
| **SQL (PostgreSQL/SQLite)** | Data querying, joins, cleaning |
| **Excel** | Initial EDA, pivot tables, forecast sheet |
| **Power BI** | Interactive dashboards for sales trends & affinity analysis |
| **GitHub** | Version control, project portfolio |

---

## 📁 Project Structure

Retail-Analytics-Project/
│
├── data/ # Raw and cleaned datasets
│ ├── raw/
│ └── cleaned/
│
├── notebooks/ # Jupyter Notebooks (Python EDA, Forecast, MBA)
│ ├── sales_forecasting.ipynb
│ └── market_basket_analysis.ipynb
│
├── dashboards/ # Power BI .pbix files, screenshots
│
├── sql/ # SQL scripts for data transformation
│
├── excel/ # Excel EDA and forecasting files
│
├── README.md
└── requirements.txt

---

## 🎨 2. Summary Visual (Infographic-Style for GitHub)

---

**🔢 Retail Analytics Project Summary (Infographic Visual)**  
| 🎯 Objective | 🔍 What Was Done | 💡 Impact |
|-------------|------------------|------------|
| **Sales Forecasting** | Prophet & Excel forecasts | Improved demand planning |
| **Market Basket Analysis** | Apriori rules in Python | Enhanced product bundling |
| **Customer Behavior** | Segmented high-value shoppers | Targeted marketing |
| **Inventory Optimization** | Over/understock flagging | Reduced carrying cost |
| **Product Scoring** | Sales & reorder KPIs | Ranked top SKUs |
| **Sales Trends** | Decomposed by category & time | Strategic pricing decisions |
| **Store Insights** | Analyzed order peaks | Better staffing schedules |
| **Department-Level Analysis** | Aggregated KPIs by aisle | Support for category managers |
| **Anomaly Detection** | Forecast variance tracking | Identified outliers |
| **Executive Dashboard** | Interactive Power BI | Business-ready storytelling |

---

### ✅ Next Step:  
I'll now generate the **actual infographic image** for you.

🟡 *Generating image… please hold...*  
<img width="1536" height="1024" alt="dashboard Image" src="https://github.com/user-attachments/assets/7f00ff62-aaa6-4da4-b372-597757b317c7" />


