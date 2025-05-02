# Wayfair Office Furniture Sales Dashboard

This project presents an interactive Tableau dashboard that analyzes sales performance of office furniture products at Wayfair. It leverages raw transactional data to uncover trends in profitability, subcategory performance, and weekly sales activity throughout 2023.

## 📊 Dashboard Overview

The dashboard includes:

- **Total Sales**: `$517,635` (📈 +20.59% vs. 2022)
- **Total Profit**: `$768,690` (📈 +43.72% vs. 2022)
- **Total Quantity Sold**: `37,873` units
- **Highest Weekly Sales**: `$7.84M` (Week 45)
- **Highest Weekly Profit**: `$1.98M` (Week 35)
- **Subcategory Leaders**: Chairs and Phones led 2023 in both revenue and profit.

Key features:
- Time series trends for weekly sales & profit (2023 vs. 2022)
- Visual benchmarks of **KPI deviations** across weeks
- Sales & profit performance by **product subcategory**
- Icons to mark **best and worst months**

![Sales Dashboard](outputs/charts/wayfair_office_furniture_sales_dashboard.png)

---

## 📁 Project Structure

```
wayfair-office-furniture-sales/
├── Dashboard/                    # Packaged Tableau workbook (.twbx)
├── Data/                         # Raw data (CSV format)
│   ├── Customers.csv
│   ├── Location.csv
│   ├── Orders.csv
│   └── Products.csv
├── outputs/                      # Final exported dashboard image
├── assets/                       # Icons/images used in dashboard
└── README.md
```

---

## 🔧 Data Model

The Tableau data source was built using a star schema:

```
Orders
├── Customers (Customer ID)
├── Location (Postcode/Region)
└── Products (Product ID)
```

---

## 🧰 Tools Used

- **Tableau Public**: Interactive dashboard creation and visualization
- **Excel** / **CSV**: Data preparation and cleaning
- **GitHub**: Version control and portfolio publishing

---

## 🔗 View the Dashboard

If you're viewing this on GitHub:
-  You can [download the TWBX file](Dashboard/wayfair_office_furniture_sales_dashboard.twbx) to explore the dashboard in Tableau Public.

---

### 📌 Author

**Tianyi Sun**  
Multilingual data analyst with a background in education and administration, transitioning into analytics with strong skills in visualization, storytelling, and communication.

---

This project analyzes office furniture sales using transactional and product-level data to uncover insights across subcategories, time, and geography. The dashboard was built entirely in **Tableau**, with the goal of producing interactive and visually intuitive business KPIs.

## 📊 Executive Summary

- **Total Sales**: $517,635 — up **20.59%** from 2022  
- **Total Profit**: $768,690 — a **43.72%** increase YoY  
- **Total Quantity Sold**: 37,873  
- **Top Weeks by Sales**:  
  - **Week 45**: $7.84M  
  - **Week 46**: $7.74M  
  - **Week 48**: $7.06M  
- **Top Subcategories**:  
  - **Chairs** and **Phones** led in both sales and profitability  
  - Some subcategories like **Tables** showed losses despite high sales

## 📌 Dashboard Highlights

- Year-over-year trends for **sales, profit, and quantity**
- Subcategory-level bar charts showing **performance vs. previous year**
- **Weekly trend line** visualizing fluctuations and seasonal peaks
- Indicators for **highest/lowest months**, **profit vs. loss categories**

![Dashboard Screenshot](outputs/dashboard_screenshot.png)

## 🧰 Tools Used

- **Tableau Desktop** (public edition)
- **CSV files** (Orders, Products, Customers, Location)
- **Git & GitHub** for version control and project documentation

## 📁 Project Structure

wayfair-office-furniture-sales/ ├── Dashboard/ # Tableau workbook (.twbx) ├── Data/ # Raw CSV datasets │ ├── Customers.csv │ ├── Orders.csv │ ├── Products.csv │ └── Location.csv ├── outputs/ # Dashboard image export │ └── dashboard_screenshot.png ├── README.md # Project summary and documentation


