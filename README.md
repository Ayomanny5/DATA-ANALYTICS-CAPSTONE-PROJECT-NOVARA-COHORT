# 📦 Novara Cohort — Data Analytics Capstone Project (Excel) 

> A full end-to-end Excel analytics project analyzing **2,098 sales transactions** across four Nigerian cities to surface revenue, profitability, and customer insights through KPI calculations, pivot tables, and an interactive dashboard.

---

## 📌 Project Overview

This capstone project was completed as part of the **Novara Data Analytics Cohort**. The goal was to simulate a real-world business scenario: taking raw sales data, cleaning and transforming it, computing key financial metrics, and building a polished executive dashboard that enables data-driven decision-making.

The dataset spans sales activity across **Nigeria's four major commercial cities** — Lagos, Kano, Port Harcourt, and Abuja — covering multiple product categories, sales channels, and customer types.

---

## 📊 Top-Line KPIs

| Metric | Value |
|---|---|
| 💰 Total Revenue | ₦2,328,370,000 |
| 🏭 Total COGS | ₦1,862,696,000 |
| 📈 Total Profit | ₦465,674,000 |
| 👥 Total Customers | 2,098 |
| 📉 Avg Profit Margin | **20%** |

---

## 🗂️ Dataset

The raw data consists of **2,098 transaction records** with the following fields:

| Column | Description |
|---|---|
| `Date` | Transaction date |
| `Region` | North / South / East / West |
| `City` | Lagos, Kano, Port Harcourt, Abuja |
| `Customer Type` | Retail / Corporate |
| `Channel` | Online / Store |
| `Product` | Product name |
| `Category` | Electronics, Furniture, Home Appliances |
| `Unit Price` | Selling price per unit (₦) |
| `Quantity` | Units sold |
| `Sales Rep` | Assigned sales representative |
| `Cost Price` | Cost of goods per unit (₦) |

---

## 🔧 Tools & Techniques

- **Microsoft Excel** — full analytics pipeline from raw data to dashboard
- **Data Cleaning** — verified data integrity; no missing or erroneous values found
- **Feature Engineering** — computed `Revenue`, `COGS`, and `Profit` columns using Excel formulas
- **Pivot Tables** — aggregated performance across products, sales reps, cities, channels, and months
- **Charts & Visualizations** — bar charts for product profitability, sales rep revenue, city-level COGS, and monthly customer trends
- **Dashboard Design** — consolidated all visuals into a single-view interactive dashboard
- **Slicers** — added `Region` and `Category` slicers for dynamic filtering

---

## 🏗️ Workbook Structure

```
Novara_Capstone.xlsx
├── Instructions      ← Project brief and task requirements
├── Sales Data        ← Raw transaction data (2,098 rows)
├── Worksheet         ← Cleaned data + Revenue, COGS, Profit columns
├── Pivot             ← Pivot tables for all analytical dimensions
├── Calc              ← Aggregated KPIs and summary metrics
└── Dashboard         ← Interactive dashboard with charts and slicers
```

---

## 📈 Key Findings

### 🏆 Top Products by Profit

| Product | Profit (₦) |
|---|---|
| Laptop A13 | 105,336,000 ✅ |
| Sofa Classic | 69,248,000 |
| Desktop PC D21 | 68,640,000 |
| Smartphone Z10 | 51,950,000 |
| Refrigerator R55 | 48,312,000 |
| Blender B10 | 6,870,000 |

> **Insight:** Laptop A13 is the star product, generating more than **22% of total company profit** on its own.

---

### 👤 Sales Rep Performance by Revenue

| Sales Rep | Revenue (₦) |
|---|---|
| Peter | 434,805,000 ✅ |
| Musa | 397,665,000 |
| David | 378,660,000 |
| Aisha | 378,035,000 |
| Chidinma | 371,370,000 |
| Grace | 367,835,000 |

> **Insight:** Peter leads the team with ₦434.8M in revenue — about **18.7% of total revenue**. The team is relatively balanced, with a spread of just ₦67M between top and bottom performers.

---

### 🏙️ City COGS Breakdown

| City | COGS (₦) |
|---|---|
| Lagos | 493,812,000 |
| Kano | 486,788,000 |
| Port Harcourt | 458,784,000 |
| Abuja | 423,312,000 |

> **Insight:** Lagos and Kano drive the highest cost volume, indicating they are the busiest sales markets and likely warrant the most operational investment.

---

### 📅 Monthly Customer Volume

| Month | Customers |
|---|---|
| Jan | 409 |
| Feb | 359 |
| Mar | 409 |
| Apr | 380 |
| May | 59 |
| Jun | 60 |
| Jul | 74 |
| Aug | 70 |
| Sep | 59 |
| Oct | 77 |
| Nov | 85 |
| Dec | 57 |

> **Insight:** There is a dramatic drop in activity from **April to May** (380 → 59 customers), with Q1 consistently being the strongest quarter. September and December represent the lowest-traffic months, suggesting seasonal dips worth investigating.

---

### 🛒 Sales Channel Performance

| Channel | Profit (₦) |
|---|---|
| Store | 247,756,000 ✅ |
| Online | 217,918,000 |

> **Insight:** In-store sales slightly outperform online — though the gap is narrow (~13%), suggesting both channels are well-established and worth investing in.

---

## 💡 Business Recommendations

1. **Double down on Laptop A13** — it is the single most profitable product; ensure consistent stock availability especially in Q1.
2. **Investigate the Q2 drop-off** — the steep decline from April to May needs further investigation; it may reflect seasonal demand, data gaps, or external market factors.
3. **Replicate Peter's approach** — his sales strategy and customer engagement could be documented and shared across the team to lift underperforming reps.
4. **Optimize Abuja operations** — Abuja has the lowest COGS, which may signal untapped revenue opportunity if marketing investment increases in that region.

---

## 🚀 Getting Started

1. **Clone or download** this repository
2. **Open** the `.xlsx` file in Microsoft Excel (2016 or later recommended)
3. Navigate to the **Dashboard** tab for the full interactive view
4. Use the **Region** and **Category slicers** to filter all charts dynamically
5. Explore the **Pivot** and **Calc** tabs for granular breakdowns

> ⚠️ **Note:** Slicers and pivot functionality may behave differently in Google Sheets or LibreOffice Calc. Microsoft Excel is recommended for the best experience.

---

## 🧠 Skills Demonstrated

- ✅ Data validation and integrity checks
- ✅ Financial KPI calculation (Revenue, COGS, Profit, Margin)
- ✅ Multi-dimensional pivot table analysis
- ✅ Chart selection and business-oriented data visualization
- ✅ Executive dashboard design with interactive slicers
- ✅ Insight generation and actionable business recommendations

---

## 🎓 About

This project was completed as the capstone submission for the **Novara Data Analytics Cohort**. It demonstrates the ability to work independently through a complete analytics workflow — from raw transactional data to a polished, insight-driven dashboard.

---

## 📄 License

This project is open for educational and portfolio purposes. All data used is fictional and created for training purposes within the Novara Cohort program.
