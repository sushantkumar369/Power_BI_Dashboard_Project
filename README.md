# Power_BI_Dashboard_Project
# 📊 Super Store Sales Dashboard

An interactive **Power BI** dashboard analyzing sales, profit, and delivery performance for a retail "Super Store" dataset — built as a single, dense executive-summary page.

## Overview

This report gives a 360° view of sales performance across regions, product categories, customer segments, and shipping methods, combining KPI cards, trend charts, and a geographic map on one page.

## 🔑 Key Metrics (KPI Cards)
- **Total Sales**
- **Total Profit**
- **Total Quantity Sold**
- **Average Delivery Time**

## 📈 Visuals Included
| Visual | Chart Type | Insights Shown |
|---|---|---|
| Sales by Sub-Category | Clustered Bar Chart | Sales performance broken down by product Category and Sub-Category |
| Sales Trend Over Time | Area Chart | Sales trend by Order Date, split by Category |
| Profit Trend Over Time | Area Chart | Profit trend by Order Date, split by Category |
| Sales by Category | Clustered Bar Chart | Category-level sales comparison |
| Sales by Ship Mode | Clustered Bar Chart | Sales distribution across shipping methods |
| Sales by Payment Mode | Donut Chart | Payment method mix by Category |
| Sales by Region & Segment | Donut Chart | Regional sales split by customer Segment |
| Sales by Segment | Donut Chart | Customer segment contribution to sales |
| Sales by State | Map | Geographic distribution of sales and top Product Names by State |
| Region Slicer | Slicer | Filter the entire report by Region |

## 🧩 Data Model

The dataset (classic "Superstore"-style retail data) includes fields such as:
- **Dimensions:** Category, Sub-Category, Region, Segment, Ship Mode, Payment Mode, State, Product Name, Order Date
- **Measures:** Sales, Profit, Quantity, Average Delivery Time (custom measure)

## 🎨 Design
- Fluent 2 theme with a custom blue background and accent color palette
- Single-page, dashboard-style layout (1920×1080) optimized for a full-screen view
- Region slicer enables cross-filtering across all visuals

## 🛠️ Tools Used
- **Power BI Desktop** — data modeling, DAX measures, and report design
