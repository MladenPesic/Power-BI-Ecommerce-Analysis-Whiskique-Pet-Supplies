# 📊 Power BI Ecommerce Analysis — Whiskique Pet Supplies

## 📁 Project Overview

This project presents a complete end-to-end analysis of ecommerce operations for **Whiskique**, a fictional online pet supply company. The goal was to deliver actionable insights and interactive dashboards to support business decisions in:

- **Sales performance and profitability**
- **Customer behavior and segmentation**
- **Shipping cost optimization**
- **Product-level cross-sell and upsell strategies**

The final deliverable is a Power BI report composed of three executive-style dashboards tailored to senior stakeholders.

---

## 🎯 Business Objectives

Whiskique's leadership had two key business goals:

1. **Grow revenue** through better customer insights and data-driven cross-sell/upsell strategies.  
2. **Reduce operational costs**, particularly in shipping, to improve profit margins.

This report supports both objectives with clear, data-driven recommendations.

---

## 🧠 Key Insights

- 📦 **High-impact cross-sell opportunities** identified through market basket analysis  
- 🔁 **Upsell strategies** (e.g., “buy more, save more”) tested using interactive what-if simulations  
- 🚚 **Shipping cost modeling** demonstrated potential savings of up to **70%** per shipment  
- 🧭 **Profitability breakdowns** highlighted which products and regions to prioritize for investment

---

## 🛠️ Tools & Techniques

| Tool        | Usage                                                       |
|-------------|-------------------------------------------------------------|
| Power BI    | Data modeling, DAX calculations, interactive dashboards     |
| Power Query | Data cleaning, transformation, and normalization            |
| DAX         | KPIs, dynamic measures, what-if analysis                    |
| CSV files   | Data source for sales, customers, products, and region data |

---

## 📈 Dashboard Pages

### 1️⃣ Executive Summary

**Purpose:** High-level business pulse  
**Includes:**

- Total Sales, Total Profit, Profit %
- Sales and profit by product and region
- Profit margin by product category
- Filter panel for product and state

> 📌 *Equips leadership with a snapshot of performance across key dimensions.*

---

### 2️⃣ Shipping Metrics

**Purpose:** Understand cost dynamics and upsell levers  
**Includes:**

- Baseline vs. what-if shipping cost comparison
- Interactive what-if slider (quantity: 1–20 units)
- Running total of shipping cost over time
- Breakdown by product, state, region

> 📌 *Supports logistics planning and potential cost-saving strategies.*

---

### 3️⃣ Market Basket Analysis

**Purpose:** Identify product pairing opportunities  
**Includes:**

- Most frequently co-purchased items
- Profitability of suggested cross-sell items
- Visuals linking primary + secondary products

> 📌 *Informs product bundling and promotional strategies to increase AOV.*

---

## 📊 Sample KPIs & Metrics

| KPI                            | Description                                             |
|--------------------------------|---------------------------------------------------------|
| `Number of Customers`          | Distinct customers (excluding blanks)                  |
| `Customer LTV (avg)`           | Lifetime value = Total Sales per Customer              |
| `Shipping (Baseline)`          | Original cost model                                    |
| `Shipping (What-if)`           | Quantity-based discounted shipping                     |
| `Shipping (Difference)`        | Modeled savings per upsell                             |
| `Profit (Baseline)`            | Sales – COGS – Shipping                                |
| `Profit %`                     | Profitability as a percentage                          |
| `Blended Shipping Cost Factor` | Dynamic DAX logic adjusting cost by quantity bracket   |

---

## 🧱 Data Model Structure

**Fact Table:**

- `Sales`

**Dimension Tables:**

- `Customers`
- `Products`
- `State Mapping`

**Derived Tables:**

- `Invoice Totals`
- `Market Basket` (self-joined on invoice)

**Key Relationships:**

- Customer ID → Customer Table  
- Stock Code → Product Table  
- State → Region Mapping

---

## ✅ Outcome

This project showcases how a well-modeled Power BI report can:

- Enable strategic business decisions
- Identify cost-saving opportunities
- Improve operational efficiency
- Guide targeted marketing efforts

> 💼 Ideal for stakeholders in ecommerce, supply chain, and marketing analytics.
