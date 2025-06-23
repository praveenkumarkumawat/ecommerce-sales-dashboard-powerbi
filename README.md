# E-commerce Sales & Delivery Dashboard – Power BI Project

This Power BI project provides a comprehensive analysis of an e-commerce dataset, with a focus on sales performance, customer behavior, and delivery efficiency. The dashboard is built using 3 interactive pages (Sales Overview, Product & Customer Analysis, and delivery Performance) and combines visuals, KPIs, and filtering to deliver actionable insights.

---

## Dataset Overview

The dataset includes fictional e-commerce transactions with:
- Product & Category
- Quantity, Unit Price, Total Price, Final Price, Discount
- Delivery Time (Days), Location, Payment Method
- Order ID, customer ID
- Purchase Date

---

## Dashboard Pages

### 1. Sales Overview
- KPIs: Total Sales, Total Orders, Total Discount, Average Order Value
- Line Chart: Monthly Sales Trend
- Bar Chart: Order Count by Product Category
- Pie Chart: Payment Method Distribution
- Map/Treemap: Sales by Location or Zone
- Slicers: Category, Year, Payment Method

---

### 2. Product & Customer Analysis
- Matrix Table: Category → Product with Sales, Quantity, Discount
- Bar Chart: Top 10 Products by Sales
- Pie Chart: Sales Segmentation by Order Value (Low < 1500/Medium/High >3000)
- Bar Chart: Order Count by Sales Range
- Stacked Column Chart: Count of Category & Payment Method
- Slicers: Category, Year, Sales Range (Low, Medium, High) Payment Method

  ---

  ### 3. Delivery Performance
- KPIs: Avg. Delivery Time, Fast Deliveries %, Late Deliveries %, Total Orders
- Line Chart: Average Delivery Time by Month
- Pie Chart: Fast vs. Slow Deliveries
- Column Chart: Delivery Time Distribution (Histogram)
- Slicers: Category, Year, Payment Method

---

## Tools & Techniques Used
- Power BI Desktop
- DAX (for custom KPIs like Fast Deliveries %)
- Power Query (for column creation and transformation)
- Visual formatting & interactive filtering

---

## Key Insights
- Most orders fall into the medium order value bracket
- Clothing is the most frequently ordered category
- About 32% of deliveries are completed within 3 days
- Delivery time fluctuates significantly across months and regions

---

## 📸 Screenshots

| Sales Overview | Delivery Performance |
|----------------|----------------------|
| ![Sales Overview](screenshots/dashboard-overview.png) | ![Delivery](screenshots/delivery-page.png) |

## How to Use

1. Clone or download the repo
2. Open `ecommerce_sales_dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Interact with slicers and explore each dashboard page

