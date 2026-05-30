# Global Sample Store Analytics Dashboard

An interactive, 4-page Power BI dashboard transforming raw retail transactions into structured executive insights across regional, customer, and temporal dimensions.

---

### Core DAX Metrics Illustrated
```dax
Total Cost = [Purchase Unit Cost]*[Quantity]
Total Discount = ([Selling Unit Price (Pre Discount)]*[Discount%]) * [Quantity]
Total Profit = [Total Sales]-[Total Cost]
Total Sales = ([Selling Unit Price (Pre Discount)]*(1 -[Discount%]) )*[Quantity]
```
---

### Dashboard Structure & Insights

#### Page 1: Executive KPI Overview & Map
* **Core Metrics:** Displays Total Profit ($286.22K), Total Sales ($2.3M), 5,009 Total Orders, 38K Units Sold, and 793 unique customers.
* **Visual Structure:** A dynamic, interactive Bing map detailing **Total Sales by State** across North America.

#### Page 2: Category & Trend Intelligence
* **Categorization:** Breakdown of Total Sales across product segments (**Technology, Furniture, Office Supplies**) and consumer profiles (**Consumer, Corporate, Home Office**).
* **Geographic Share:** Donut chart evaluating **Total Sales by Region** (West leads at 31.58%, followed by East at 29.55%).
* **Temporal Tracking:** Interactive Waterfall Chart tracking progressive sales growth over quarters from 2014 through 2017.

#### Page 3: Customer & Product Drill-Down
* **Operational Highlights:** Identifies **Monday, Friday, and Sunday** as the top 3 highest-grossing transaction days ($1.24M combined).
* **High Performers:** Evaluates top 5 cities (led by **New York City** and **Los Angeles**), top 10 customers (led by Sean), and top 10 revenue-generating products (led by the **Canon imageCLASS 2200 Advanced Copier**).

#### Page 4: Temporal Slicer & Ad-Hoc Explorer
* **Advanced Filtering:** Deep-dive reporting matrix analyzing **Total Sales and Total Profit by Order Day** (identifying **Sunday** as the most profitable day at $57K).
* **Granular Controls:** Multi-select slicers mapping 17 product sub-categories (Accessories, Binders, Tables, etc.) across 4 core regions.

---

### Core Insights Discovered
1. **West Coast Dominance:** The West Region represents the largest market share, bringing in **31.58% ($725.46K)** of total organizational sales.
2. **The Sunday Margin Paradox:** While Monday generates marginally higher overall sales volume, **Sunday acts as the most profitable day of the week**, yielding **$57K** in total net profits.
3. **Product Revenue Anchors:** High-ticket technology assets like the **Canon imageCLASS 2200 Advanced Copier** drastically outpace standard office supplies in driving macro revenue numbers.

---
