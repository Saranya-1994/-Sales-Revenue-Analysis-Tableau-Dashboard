# 📊 Sales & Revenue Analysis — Tableau Dashboard

> An interactive Tableau dashboard analyzing **4 years of sales data (2017–2020)** across Indian markets, covering revenue trends, market performance, top products, and customer insights.

---

## 🔗  Dashboard
<img width="1613" height="925" alt="Screenshot 2026-04-15 110126" src="https://github.com/user-attachments/assets/839a5b44-f0d2-46b3-9f41-41099c37340e" />


---

## 📌 Project Overview

This project analyzes sales and revenue data for a hardware distribution business operating across major Indian cities. The dashboard enables business stakeholders to monitor KPIs, identify top-performing markets and products, and track revenue trends over time.

| Metric | Value |
|---|---|
| Total Revenue | ₹986.63M |
| Total Sales Quantity | 2,431.63K units |
| Period Covered | 2017 – 2020 |
| Markets | 15 Indian cities |
| Top Market | Delhi NCR — ₹520.79M |
| Top Product | Prod040 — ₹23.58M |
| Top Customer | Electricalsara Stores — ₹413.91M |

---

## 📂 Repository Structure

```
sales-revenue-analysis-tableau/
│
├── README.md
├── dataset/
│   └── sales_data.xlsx          # Raw dataset (transactions, customers, markets, products)
├── tableau/
│   └── sales_revenue_dashboard.twbx   # Tableau packaged workbook
└── screenshots/
    └── dashboard_overview.png   # Dashboard preview
```
---

## 📈 Dashboard Features

### KPI Cards
- **Total Revenue** — normalized revenue across all markets
- **Sales Quantity** — total units sold

### Revenue by Market
Horizontal bar chart ranking all 15 markets by normalized revenue. Delhi NCR dominates with ₹520.79M, followed by Mumbai (₹150.18M) and Ahmedabad (₹132.53M).

### Sales Quantity by Market
Volume-based market ranking. Delhi NCR leads with 989,991 units, followed by Nagpur (262,094) and Ahmedabad (207,104).

### Revenue by Year (2017–2020)
Line chart showing monthly revenue trends across four years. Revenue peaked in 2018 (~₹42.52M) and shows a declining trend through 2020.

### Top 10 Products
Bar chart of highest-revenue products. Prod040 leads at ₹23.58M, followed by Prod159 (₹17.66M) and Prod065 (₹16.26M).

### Top 10 Customers
Bar chart of highest-value customers. Electricalsara Stores is the dominant customer at ₹413.91M, far ahead of Electricalslytical (₹49.64M).

---

## 🔍 Key Insights

- **Delhi NCR is the primary revenue driver**, contributing over 52% of total revenue — heavy geographic dependency.
- **Revenue peaked in 2018** and has been declining steadily; 2020 shows the sharpest monthly drops (down to ₹14.71M).
- **Electricalsara Stores accounts for a disproportionate share** of customer revenue, indicating key account concentration risk.
- **Ahmedabad and Nagpur** show strong sales volume relative to revenue, suggesting lower average selling prices in those markets.

---

## 🛠 Tools Used

| Tool | Purpose |
|---|---|
| Tableau Desktop | Dashboard design & visualization |
| Microsoft Excel | Data source |
| SQL | Data extraction & preparation |

---

## 📁 Dataset

The dataset includes the following tables:
- `transactions` — order-level sales records
- `customers` — customer names and types
- `markets` — city and zone information
- `products` — product codes and types
- `date` — calendar dimension for time intelligence

> Source: [Codebasics — Sales Insights Project](https://codebasics.io/resources/sales-insights-data-analysis-project)

---


---

