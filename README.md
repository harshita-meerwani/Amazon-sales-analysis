# 📊 Amazon Sales Analysis Dashboard

## 🚀 Overview

This project presents an analysis of Amazon e-commerce sales data using SQL, Python (Jupyter Notebook), and Power BI.

The objective is to understand customer behavior, product performance, and overall business trends through interactive dashboards.

---
## 📊 Dashboard Previews

### 🧭 Executive Dashboard
![Executive Dashboard](Executive%20dashboard.png)
> High-level KPIs: ₹90.50M total revenue, 37.65% gross margin, 2K orders, and year-over-year growth tracking.

### 👥 Customer Analysis
![Customer Analysis](customer%20dashboard.png)
> 500 customers, 92.20% retention rate, top customer segments, revenue by state, and loyalty point distribution.

### 📦 Product Analysis
![Product Analysis](Product%20dashboard.png)
> 6K units sold, ₹28.83M gross profit, top brands by revenue, cancellation rates, and subcategory breakdown.

---

## 🗂️ Project Structure

```
📁 Amazon-Ecommerce-Analytics/
├── 📓 amazon_ecommerce.ipynb      # SQL-based analysis notebook
├── 📊 Amazon_ecommerce.xlsx       # Source dataset (4 sheets)
├── 🖼️ Executive_dashboard.png     # Power BI – Executive view
├── 🖼️ customer_dashboard.png      # Power BI – Customer analysis
├── 🖼️ Product_dashboard.png       # Power BI – Product analysis
└── 📄 README.md
```

---

## 📁 Dataset Overview

The dataset is stored in `Amazon_ecommerce.xlsx` with **4 relational sheets**:

| Table | Rows | Description |
|-------|------|-------------|
| `Orders` | 2,000 | Transactions with pricing, discounts, tax, shipping, order status |
| `Customers` | 500 | City, state, segment, loyalty points |
| `Products` | 144 | Category, brand, cost, sale price, product rating |
| `Returns` | 167 | Return reasons and refund amounts |

---

## 🔑 Key Business Metrics

| Metric | Value |
|--------|-------|
| 💰 Total Revenue | ₹90.50M |
| 📦 Total Orders | 2,000 |
| 📈 Gross Margin | 37.65% |
| 🔄 Return Rate | 8.35% |
| 🛒 Avg Order Value | ₹45.25K |
| 👤 Total Customers | 500 |
| 🔁 Repeat Customers | 461 |
| ❤️ Retention Rate | 92.20% |

---

## 🧠 Analysis Highlights

### 📈 Year-over-Year Growth
- Revenue grew **106%** from ₹1.99Cr (2022) to ₹4.10Cr (2024)
- Gross margin stayed stable ~37–38%, indicating costs rising proportionally with revenue

### 🛍️ Top Product Categories
- **Beauty** leads with ₹1.70Cr across 341 orders
- **Sports** is close behind at ₹1.69Cr
- **Books** has the highest order count (349) but lower revenue due to lower unit price

### 👑 Top Customers
- **Deepak Shah** (Surat) — Top spender at ₹5.83L across 9 orders
- **Priya Reddy** (Mumbai) — Most orders (12) with ₹5.25L spend
- 3 of the top 10 customers are from **Surat** — a high-potential market

### 💳 Payment Methods
- Credit Card and Cash on Delivery dominate
- EMI users tend to place higher-value orders

### 🌍 Revenue by State
| State | Revenue |
|-------|---------|
| Gujarat | ₹18.15M |
| Maharashtra | ₹17.11M |
| West Bengal | ₹11.18M |
| Delhi | ₹10.13M |
| Rajasthan | ₹9.40M |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Data loading, SQL execution, analysis |
| **Pandas** | DataFrame operations and data wrangling |
| **SQLAlchemy + SQLite** | In-memory relational database for SQL queries |
| **Jupyter Notebook** | Interactive analysis with narrative insights |
| **Microsoft Excel** | Source data storage (4 relational sheets) |
| **Power BI** | Interactive dashboard creation and visualization |

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas openpyxl sqlalchemy
```

### Run the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/harshita-meerwani/amazon-ecommerce-analytics.git
   cd amazon-ecommerce-analytics
   ```

2. Update the file path in the notebook:
   ```python
   FILE_PATH = "G:\Amazon dashboard\Amazon_ecommerce.xlsx"  # relative path
   ```

3. Open and run the notebook:
   ```bash
   jupyter notebook amazon_ecommerce.ipynb
   ```

---

## 📓 Notebook Structure

The Jupyter notebook contains **queries** organized around key business questions:

- 📅 **YoY Growth** — Revenue, orders, and margin trends
- 🗂️ **Category Analysis** — Top-performing product categories
- 👥 **Customer Segmentation** — Consumer vs Corporate vs Home Office
- 💳 **Payment Preferences** — Method-wise order value and volume
- 📦 **Returns Analysis** — Return rates by category and reason
- 🌐 **Geographic Insights** — State and city-level revenue breakdown
- 🏆 **Brand Performance** — Top brands by revenue and gross profit
- 🔁 **Retention & Loyalty** — Repeat purchase behavior and loyalty tiers

Each query is followed by a **business insight** explaining the "so what" behind the numbers.

---

## 📌 Key Insights Summary

> 💡 The business doubled revenue in 2 years but margins stayed flat — growth is real, but profitability needs attention.

> 💡 Surat is an emerging power market with 3 of the top 10 spenders.

> 💡 92.2% retention rate is exceptional — the loyalty program is clearly working.

> 💡 Beauty and Sports are the revenue engines; Electronics has room to grow.

> 💡 Return rate at 8.35% — Beauty and Books have the most returns (32 each).

---


