# JustDrinks Ltd — Sales, Inventory & Vendor Analysis
**Tool:** Power BI | **Data:** 12-month financial year | **Locations:** 80+ retail stores

---

## Background

JustDrinks Ltd is a major alcoholic drinks retailer operating across the fictional state of Lincoln, with over 80 store locations and annual sales exceeding $450 million. This project was completed as a data analyst capstone, covering a full year of sales, inventory, purchasing, and vendor data.

The goal was straightforward — dig into the numbers, find out what the business is doing well, where it's losing ground, and give leadership something they can actually act on.

---

## What's in this repo

```
├── JustDrink_Capstone_Project.pbix   # Full Power BI report file
├── screenshots/                       # Dashboard previews
│   ├── sales_overview.png
│   ├── vendor_activity.png
│   ├── inventory_analysis.png
│   └── store_performance.png
└── README.md
```

> Open the .pbix file in Power BI Desktop to explore the full interactive report.

---

## Questions this project answers

**Sales & Category Performance**
- How does revenue split between Wine and Spirits — by value, volume, and price?
- Which product sizes drive the most sales in each category?
- Which stores have the highest and lowest average selling prices?

**Vendor Activity**
- Which vendors account for the largest share of total purchases?
- How did purchasing patterns shift across the 12-month period?
- Who are the critical suppliers based on spend and order frequency?

**Inventory & Shelf Time**
- How does stock purchased compare to stock sold across the year?
- Which products sit on shelves the longest before moving?
- Are there seasonal patterns affecting how quickly inventory turns over?

**Strategic Insights**
- Which vendors, stores, and products drive the most profitability?
- Where are the biggest opportunities to improve margins?

---

## Key findings

- **Spirits outsell Wine by volume** but Wine holds a higher average selling price across most store locations
- **A small group of vendors** accounts for a disproportionate share of total purchase value — concentration risk worth monitoring
- **Certain product sizes** consistently outperform others in both categories, pointing to where shelf space is best spent
- **Slow-moving SKUs** were identified across specific stores, tying up inventory spend without return
- **Seasonal purchasing spikes** were visible in Q4, not always matched by equivalent sales movement

---

## Dashboards built

| Dashboard | What it covers |
|---|---|
| Sales Overview | Total revenue, Wine vs Spirits breakdown, monthly trends |
| Store Performance | Average selling price by store, top and bottom performers |
| Vendor Activity | Purchase value by vendor, 12-month trend, supplier ranking |
| Inventory Analysis | Stock purchased vs sold, shelf time by product, turnover rate |

---

## Data preparation

Before building anything, the datasets went through a cleaning pass — checking for missing values, duplicate records, inconsistent formatting across the sales, inventory, and purchasing tables. The data was then structured into a single reporting model in Power BI to make cross-dataset analysis reliable.

---

## Tools used

- **Power BI Desktop** — data modelling, DAX measures, dashboard design
- **Power Query** — data cleaning and transformation

---

## About

Completed as part of a data analytics capstone. Dataset is fictional and provided for educational purposes.
