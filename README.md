# Power-BI-Projects-
# Quarterly Financial Performance & Sales Analysis (XYZ Ltd.)

An interactive business intelligence dashboard analyzing quarterly financial performance, product profitability, state-level revenue distribution, and customer payment behaviors for XYZ Ltd.

---

## 📊 Dashboard Preview

![Quarterly Financial Report Dashboard](assets/dashboard_preview.png)

---

## 🎯 Executive Summary & Key KPIs

Across the quarterly dataset, XYZ Ltd. recorded:
* **Total Revenue:** 437,771 (~438K)
* **Total Profit:** 36,963 (~37K)
* **Overall Profit Margin:** 8.44%
* **Total Units Sold:** 6,000 (6K)

---

## 🔍 Core Insights & Findings

### 1. Category & Sub-Category Performance
* **Electronics** is the largest revenue contributor (**166,267**, 7.92% margin), heavily driven by **Printers** (59,252 revenue, 14.52% margin) and **Phones** (46,119 revenue).
* **Clothing** generated **144,323** with the highest category margin at **9.23%**. **Sarees** generated the most volume/revenue (59,094), while **T-shirts** (20.32%) and **Shirts** (20.03%) delivered top percentage profitability.
* **Loss-Making Sub-Categories Identified:**
  * *Clothing:* Skirts (-16.19%), Kurtis (-11.93%), Leggings (-6.17%)
  * *Electronics:* Electronic Games (-1.64% margin / -644 profit)
  * *Furniture:* Furnishings (-5.98% margin / -806 profit)

### 2. Geographic Distribution (Top 5 States)
* **Maharashtra** leads nationwide revenue and total profit, followed closely by **Madhya Pradesh**.
* **Uttar Pradesh**, **Delhi**, and **Rajasthan** round out the top 5 revenue contributors, showing clear regional demand concentration.

### 3. Payment Mode Share
* **Cash on Delivery (COD)** dominates customer transactions at **35.45%**.
* Digital & Card payments split the remainder: **Credit Card** (19.86%), **EMI** (17.79%), **UPI** (15.68%), and **Debit Card** (11.22%).

---

## 🛠️ Tech Stack & DAX Calculations

* **BI Tool:** Power BI
* **Data Modeling:** Star Schema / Fact & Dimension Tables
* **Key DAX Measures:**
  * `Total Revenue = SUM(Sales[Revenue])`
  * `Total Profit = SUM(Sales[Profit])`
  * `Profit Margin = DIVIDE([Total Profit], [Total Revenue], 0)`
  * `Total Quantity = SUM(Sales[Quantity])`

---

## 💡 Strategic Recommendations

1. **Product Rationalization:** Review supplier pricing and discount strategies for negative-margin products (*Skirts*, *Kurtis*, *Electronic Games*, *Furnishings*) to prevent margin erosion.
2. **Promote High-Margin Winners:** Allocate more ad spend towards high-margin categories like *T-shirts*, *Shirts*, *Accessories*, and *Printers*.
3. **Incentivize Digital Payments:** Since COD represents >35% of orders (higher return/cancellation risk), introduce small discount incentives for UPI or Prepaid options.
