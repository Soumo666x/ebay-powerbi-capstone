# 🛍️ eBay Men's Clothing — Sales Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-600%20Products-blue?style=for-the-badge)

> A fully interactive Power BI dashboard built on 600 real eBay men's clothing
> listings — surfacing price trends, brand performance, condition breakdowns,
> and the relationship between pricing, shipping, and customer engagement.

---

## 📌 Problem Statement

The eBay men's clothing marketplace is vast and unstructured. Sellers and analysts
struggle to identify pricing patterns, brand dominance, and buyer behaviour without
a consolidated analytical view.

**This dashboard answers:**
- Which price ranges attract the most listings?
- Which brands dominate the marketplace?
- How does product condition affect listing volume?
- Is there a link between price, shipping cost, and reviews?

---

## 📊 Dashboard Overview

| Feature | Details |
|---|---|
| Tool | Microsoft Power BI Desktop |
| Pages | 1 (Single-page interactive report) |
| Canvas Size | 1280 × 720 px |
| Dataset | `ebay_mens_clothing_600_products` |
| Total Visuals | 7 |
| Slicers / Filters | 5 |

---

## 🔢 KPI Metrics (Card Visual)

| Metric | Description |
|---|---|
| Total Products | Count of all product listings |
| Total Reviews | Sum of all buyer reviews |
| Avg Shipping Cost | Average shipping cost across listings |
| Avg Price | Average selling price across listings |

---

## 📈 Visuals Included

1. **Column Chart** — Price distribution vs Count of Products
2. **Bar Chart** — Brand vs Count of Products
3. **Donut Chart** — Products by Condition (New / Used / etc.)
4. **100% Stacked Bar Chart** — Category vs Total Products & Sum of Price
5. **Scatter Chart** — Price vs Shipping Cost *(bubble size = Review Count)*
6. **Scatter Chart** — Price vs Review Count
7. **Card Visual** — KPI headline metrics

---

## 🔽 Interactive Slicers

| Slicer | Filters By |
|---|---|
| Brand | Product brand name |
| Color | Item color |
| Size | Clothing size (S / M / L / XL...) |
| Condition | New / Used / Refurbished |
| Shop by Category | eBay category classification |

---

## 🗂️ Dataset Columns

| Column | Type | Description |
|---|---|---|
| Product Name | Text | Listing title |
| Brand | Text | Brand label |
| Price | Decimal | Selling price (USD) |
| Shipping Cost | Decimal | Cost of shipping (USD) |
| Condition | Text | New / Used / etc. |
| Color | Text | Primary color |
| Size | Text | Clothing size |
| Shop by Category | Text | eBay category |
| Review Count | Integer | Number of buyer reviews |

---

## ⚙️ Tech Stack

- **BI Tool:** Microsoft Power BI Desktop
- **Query Language:** DAX (Data Analysis Expressions)
- **Data Source:** CSV dataset (600 eBay product listings)
- **File Format:** `.pbix`

---

## 🚀 Future Improvements

- [ ] Expand to 10,000+ listings with live eBay API integration
- [ ] Add a Seller Analytics page
- [ ] Time-series trend analysis by listing date
- [ ] Price prediction model using Python + Power BI
- [ ] Mobile-optimized layout for Power BI app
- [ ] Natural Language Q&A visual

---

## 📁 Files in This Repository

| File | Description |
|---|---|
| `e_bay.pbix` | Main Power BI dashboard file |
| `eBay_PowerBI_Capstone_Documentation.pdf` | Project documentation (5 pages) |

---

## 🏷️ Project Info

**Program:** Power BI Capstone Project
**Submitted:** April 21, 2026
**Tool:** Microsoft Power BI Desktop
