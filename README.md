# ☕ BrewBean Business Analytics

**End-to-end business intelligence project for a 10-outlet coffee chain — from raw transaction data to an executive dashboard and client-ready presentation.**
---

## 📌 Project Overview

BrewBean Business Analytics is a business analysis project focused on understanding **sales, customers, products, promotions, inventory, and outlet performance** across a 10-outlet coffee chain operating in Tamil Nadu.

The project covers the full analytics workflow:

1. **Clean & structure** raw operational data using Power Query
2. **Model** the data across five linked tables (transactions, inventory, products, outlets, promotions)
3. **Analyze** performance using PivotTables and calculated metrics
4. **Visualize** findings in an interactive Excel dashboard
5. **Communicate** results to stakeholders via a client-ready presentation

The goal: turn scattered records into a single, trustworthy view that management can act on.

---

## ❓ Business Questions

This analysis was built to answer the questions that actually drive day-to-day decisions:

- Which outlets generate the highest revenue and profit?
- Which beverages and food items are top-selling?
- What are the busiest hours of the day?
- Which promotional campaigns perform best?
- Which customer segments contribute the most revenue?
- Which payment methods are most preferred?
- Which products receive the highest customer ratings?
- Which outlets need operational improvement?

---

## 📊 Dataset Summary

| Metric | Value |
|---|---|
| Analysis period | Jan 1 – Jun 30, 2025 |
| Outlets | 10 (across Tamil Nadu) |
| Products tracked | 50 SKUs |
| Sales transactions | 800 |
| Inventory records | 500 |
| Promotional campaigns | 12 (8 completed, 4 planned) |
| Total revenue | ₹2.94L |
| Total profit | ₹1.76L (~60% margin) |
| Avg. customer rating | 3.99 / 5 |

---

## 💡 Key Insights

- **Outlet performance varies widely** — a ~35% revenue gap sits between the top outlet (Saravanampatti) and the lowest (Salem), pointing to cost or operational differences worth investigating.
- **Best sellers aren't always best-rated** — some high-volume products have lower customer satisfaction scores than lower-volume items, flagging a potential quality/consistency issue.
- **Inventory risk is concentrated** — roughly 1 in 4 SKUs are currently below reorder level, mostly in fast-moving coffee items.
- **Mornings drive footfall** — 8–9 AM is the busiest window, ~40% busier than the evening peak (6–7 PM).
- **Digital payments dominate** — UPI, PhonePe, Google Pay, and GPay together account for 59% of all transactions.
- **Promotions have measurable ROI** — the "Summer Chillers" campaign delivered the highest expected sales lift (~28%), making it a template for future seasonal offers.

---

## 🛠 Tools Used

- **Microsoft Excel** — data modeling, formulas, calculated fields
- **Power Query** — data cleaning, transformation, and consolidation
- **PivotTables** — multi-dimensional analysis across outlets, products, and time
- **PivotCharts** — visual breakdowns of trends and comparisons
- **Excel Dashboard** — single-page interactive summary for stakeholders

---

## 📁 Project Structure

```text
BrewBean-Business-Analytics/
├── data/
│   ├── raw/                              # Original, unprocessed source data
│   └── cleaned/                          # Data after Power Query cleaning
├── analysis/
│   └── BrewBean_Analysis.xlsx            # Core workbook: model, PivotTables, formulas
├── dashboard/
│   └── BrewBean_Dashboard.png            # Exported view of the Excel dashboard
├── presentation/
│   └── BrewBean_Client_Presentation.pptx # Client-facing summary deck
└── README.md
```

---

## 🚀 How to Use

1. Clone the repository
   ```bash
   git clone https://github.com/MiniGova/BrewBean-Business-Analytics.git
   ```
2. Open `analysis/BrewBean_Analysis.xlsx` in Microsoft Excel.
3. Review the **PivotTable** and **Dashboard** tabs for the full breakdown by outlet, product, promotion, and customer segment.
4. Refer to `dashboard/BrewBean_Dashboard.png` for a quick visual snapshot without opening Excel.
5. Open `presentation/BrewBean_Client_Presentation.pptx` for the summarized, stakeholder-ready walkthrough of findings and recommendations.

---

## 📈 Dashboard Preview

![BrewBean Dashboard](dashboard/BrewBean_Dashboard.png)

---

## ✅ Recommendations

| Priority | Action |
|---|---|
| Immediate | Review low-margin outlets (Salem, Gandhipuram, Trichy) against top performers |
| Immediate | Automate reorder alerts for SKUs below threshold |
| 30 days | Run a quality/consistency check on high-volume, lower-rated products |
| Next campaign | Replicate the "Summer Chillers" promotion format |
| 60 days | Build loyalty programs around digital/UPI payment flows |

---