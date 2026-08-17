# 📦 Amazon / E-Commerce Sales Analytics

**End-to-end data analytics project** covering data preparation, KPI modeling, and interactive Power BI dashboarding on a 4-year global e-commerce transaction dataset.

![Tools](https://img.shields.io/badge/Tools-Excel%20%7C%20SQL%20%7C%20Power%20BI-blue)
![Records](https://img.shields.io/badge/Records-51%2C290%20order--lines-informational)
![Period](https://img.shields.io/badge/Period-2011--2014-lightgrey)

---

## 📖 Overview

This project converts raw e-commerce order data into decision-ready business intelligence. Using **Excel, SQL, and Power BI**, it analyzes 51,290 order-line records spanning 4 years, 7 global markets, and 147 countries — covering sales performance, profitability, customer segments, shipping economics, and geographic trends — and translates the findings into concrete business recommendations.

**Prepared by:** Suresh Kumar
**Dataset:** `ECOMM_DATA.xlsx` (Orders, Returns, People)
**Analysis Period:** Jan 1, 2011 – Dec 31, 2014

---

## 🎯 Objectives

- Measure overall sales, profit, quantity, orders, customers, and shipping performance
- Identify high- and low-performing categories, sub-categories, markets, countries, and states
- Analyze yearly growth and profitability trends (2011–2014)
- Evaluate customer segments and shipping modes for business planning
- Build an interactive Power BI dashboard with category-level drill-down
- Translate analytical findings into practical business recommendations

---

## 🧰 Tools & Techniques

| Category | Details |
|---|---|
| **Data Preparation** | Data validation, feature engineering (Year extraction, profitability ratios, return rate) |
| **Analysis** | SQL aggregation, KPI modeling, segmentation, geographic and profitability analysis |
| **Visualization** | Power BI — KPI cards, slicers, bar charts, donut charts, drill-down views |
| **Dataset Structure** | Orders (51,290 rows × 24 cols) · Returns (1,175 rows) · People (13 rows) |

---

## 📊 Key KPIs

| KPI | Value |
|---|---|
| Total Sales | **$12.64M** |
| Total Profit | **$1.47M** (11.61% margin) |
| Total Quantity Sold | **178.3K units** |
| Orders | **25,035** |
| Customers | **1,590** |
| Markets / Countries | **7 / 147** |
| Return Rate | **4.69%** |
| Weighted Avg. Discount | **0.11%** |

---

## 🔍 Key Findings

- **Sales grew 90.3%** — from $2.26M (2011) to $4.30M (2014), with profit rising from $248.9K to $504.2K over the same period.
- **Technology** is the strongest category by both revenue ($4.74M) and margin (13.99%); **Furniture** lags at just 6.94% margin despite $4.11M in sales.
- **Tables** is the single biggest profitability concern — a loss-making sub-category at **-$64.1K**.
- **APAC** is the top market ($3.59M sales), while **EMEA** has the weakest margin (5.45%), signaling pricing/cost issues.
- **Standard Class** shipping dominates, generating $7.58M in sales (of $12.64M total).
- **Consumer** is the largest customer segment, contributing $6.51M in sales and $749.2K in profit.

---

## 💡 Business Recommendations

1. **Optimize Furniture pricing** — review supplier costs, freight, and discounting, especially for Tables
2. **Control discounting** — enforce margin-based discount thresholds
3. **Prioritize high-margin growth** — scale investment in Technology and Office Supplies
4. **Improve EMEA economics** — analyze freight, product mix, and discount behavior
5. **Investigate returns** — break down the 4.69% return rate by category, market, and segment
6. **Adopt regional pricing** — replace one-size-fits-all pricing with market-level strategy
7. **Monitor shipping economics** — improve fulfillment efficiency for Standard Class
8. **Build management alerts** — flag negative-profit products, margin decline, and unusual discounting in Power BI

---

## 📈 Dashboard Preview

The Power BI dashboard supports category-level drill-down (Furniture / Office Supplies / Technology) with dynamically updating KPI cards, country/state rankings, market mix, and shipping-mode performance.

> 🖼️ *Add dashboard screenshots here, e.g.:*
> `![Dashboard - All Categories](screenshots/dashboard_all_categories.png)`
> `![Dashboard - Technology](screenshots/dashboard_technology.png)`

---

## 📁 Repository Structure

```
├── data/
│   └── ECOMM_DATA.xlsx              # Raw dataset (Orders, Returns, People)
├── dashboard/
│   └── Amazon_Sales_Dashboard.pbix  # Power BI dashboard file
├── report/
│   └── Ecommerce_Analytics_Report.pdf  # Full project report
├── screenshots/
│   └── *.png                        # Dashboard screenshots
└── README.md
```

---

## 🚀 Key Takeaways

- Demonstrated end-to-end analytics: Excel ingestion → SQL aggregation → Power BI dashboarding
- Analyzed 51,290 order records across 147 countries and 7 markets
- Delivered actionable KPIs and translated them into pricing, product, and logistics recommendations
- Identified a material profitability issue (Tables sub-category) invisible from revenue alone

---

## 🔮 Next Steps

- Monthly sales trend page
- Customer lifetime-value (CLV) analysis
- Product-level Pareto (80/20) analysis
- Return-reason breakdown
- Automated profitability alert dashboard

---

## 📫 Connect

**Suresh Kumar** — Aspiring Data Analyst
[LinkedIn](https://linkedin.com/in/sureshlakhesar) · [GitHub](https://github.com/Sureshlakhesar) · sureshkumarverma049@gmail.com
