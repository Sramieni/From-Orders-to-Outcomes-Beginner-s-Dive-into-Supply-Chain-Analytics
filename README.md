# From Orders to Outcomes: A Supply Chain Optimization Journey

**Author**: Sesha Sai Ramineni
**Tools Used**: Python (Pandas, Matplotlib, Seaborn), Jupyter Notebook

---

## 🚀 Overview

This project involved analyzing 30,871 supply chain transactions from 2015–2017 to uncover inefficiencies, customer patterns, and regional performance gaps. As a first-time analyst, my goal was to transform raw data into actionable insights that could guide smarter operational decisions. Through detailed analysis, I discovered over \$2.3 million in potential efficiency gains.

---

## 📦 Datasets Used

### 1. Orders & Shipments (30,871 records)

* Order details (quantity, product, customer, time)
* Gross sales, profit, discount
* Shipping info (scheduled vs. actual date, mode, country)

### 2. Inventory (4,200 records)

* Product name and month-year
* Stock levels and cost per unit

### 3. Fulfillment (118 records)

* Product-wise average fulfillment time

---

## 🪑 Step 1: Data Cleaning & Metrics

**Challenges Faced:**

* Inconsistent column names
* Fragmented date fields
* Invalid discount entries

**Key Fixes & Features:**

* Unified dates using Pandas
* Handled missing/invalid discounts
* Computed new financial metrics:

  * `Net Sales = Gross Sales * (1 - Discount%)`
  * `Profit Margin = Profit / Net Sales`

---

## 📊 Step 2: Sales and Profit Trends

* Sales trends revealed growth from 2015 to mid-2017, followed by a sudden drop
* Regional profit breakdown showed strong performance in Central America and Western Europe

---

## 🚚 Step 3: Shipping & Fulfillment Analysis

* \~9% of orders had shipping delays >7 days, mostly from Standard and Second Class
* Fulfillment delays found even among top-selling products

---

## 🏢 Step 4: Inventory and Product Insights

* *Perfect Fitness Rip Deck* was a best-seller with 3x average sales
* *Web Cameras* were out of stock for 23 of 36 months
* Inventory heatmaps revealed seasonal stock planning and supply gaps

---

## 🤝 Step 5: Customer Behavior

* Top customer generated over \$4,000 in net sales
* Peak order times: Fridays between 2–4 PM
* Repeat buyers made up \~30% of total customers

---

## 💲 Step 6: Financial Patterns

* Discounts >25% reduced profit margins by over 34%
* Weak correlation (r ≈ 0.12) between inventory cost and actual profit

---

## 💡 Key Business Recommendations

1. Accelerate fulfillment for high-demand products
2. Use surge pricing during peak seasons
3. Resolve chronic stockouts via better forecasting
4. Reward high-value customers through VIP programs
5. Improve economy shipping services

---

## 🔬 Final Thoughts

This project taught me that the real value of data lies in context and clarity. I learned how to take disorganized datasets and build a story from them — one that points to measurable operational improvements. As a beginner, the most rewarding takeaway was realizing how far curiosity and a few lines of Python could go.

---

Thanks for reading!
