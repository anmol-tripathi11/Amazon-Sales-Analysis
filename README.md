# 📦 Amazon Sales Analysis Dashboard

An interactive Power BI dashboard analyzing **100,000+ rows** of Amazon sales data sourced from Kaggle. Built to uncover actionable insights on revenue performance, brand rankings, category trends, order status breakdown, and city-wise sales across 5 countries.

---

### Features

- **Category Slicer** — Filter across 6 categories: Books, Clothing, Electronics, Home & Kitchen, Sports & Outdoors, Toys & Games
- **Country Slicer** — Drill down by country: India, United States, Canada, Australia, United Kingdom
- **Order Status Slicer** — Filter by Delivered, Shipped, Pending, Cancelled, Returned
- **Year Slicer** — Analyze trends year-by-year from 2020 to 2024
- **KPI Cards** — Instant view of Total Revenue, Total Orders, Average Order Value, and Total Units Sold
- **Column Chart** — Total Revenue by Category for performance comparison
- **Donut Chart** — Orders by Country distribution
- **Line Chart** — Monthly Revenue Trend to track seasonal patterns
- **Bar Chart** — Top Brands by Revenue ranking
- **Matrix Table** — Category-wise breakdown of Total Revenue, Total Orders, and Avg Discount %
- **Column Chart** — Top 5 Cities by Revenue for geo-level insights

---

### Screenshots

Dashboard View — All Filters Default

(<img width="1510" height="840" alt="Amazon-Sales-Analysis-SS1" src="https://github.com/user-attachments/assets/fbdb8601-129e-4524-b027-3ba3dc661c58" />
)

Dashboard View — Filtered by Delivered Orders & Year 2024

(<img width="1509" height="841" alt="Amazon-Sales-Analysis-SS2" src="https://github.com/user-attachments/assets/c365e667-f4ad-44ea-99e8-2f75c8e46a40" />
)

Dashboard View — Filtered by United States & Year 2024

(<img width="1511" height="834" alt="Amazon-Sales-Analysis-SS3" src="https://github.com/user-attachments/assets/0ba8244f-0cef-490e-ab3b-b1469248b464" />
)

Cleaned Dataset

(<img width="1907" height="1090" alt="Amazon-Sales-Analysis-Cleaned-Dataset-SS" src="https://github.com/user-attachments/assets/f06d447a-3aed-4469-97b6-065b53eb26cf" />
)

---

### File Structure

```
Amazon-Sales-Analysis-Dashboard.pbix
│
├── Dashboard Page 1    → Main interactive dashboard with all visuals & slicers
└── Data Model          → Cleaned & transformed Amazon dataset (100,000+ rows, 15 columns)
```

---

### Tools & Techniques Used

| Tool/Feature | Purpose |
|---|---|
| Power BI Desktop | Dashboard creation and data visualization |
| Power Query | Data cleaning, transformation & column extraction |
| DAX Measures | Custom KPIs — Total Revenue, Total Orders, AOV, Total Units, Avg Discount % |
| Slicers | Interactive filtering by category, country, order status, year |
| Column Chart | Revenue by category and top cities visualization |
| Donut Chart | Orders by country distribution |
| Line Chart | Monthly revenue trend analysis |
| Bar Chart | Top brands ranked by revenue |
| Matrix Table | Category-wise multi-metric breakdown |
| KPI Cards | Snapshot of key business metrics |
| Kaggle Dataset | Source — 100,000+ rows, 15 columns of Amazon sales data |

---

### Key Insights & Business Decisions

- Analyzed **100,000+ Amazon orders** across **6 categories** and **5 countries** covering 2020–2024
- Total revenue reached **$92M** with an Average Order Value of **$918**, indicating a mid-to-premium product mix
- **Electronics** leads all categories in both total revenue and order volume, making it the highest-performing segment
- Monthly revenue trend reveals seasonal peaks in **May–June** and **August**, useful for inventory and campaign planning
- **CoreTech and KiddoFun** emerged as top-performing brands by revenue, highlighting key supplier relationships
- **Charlotte, Dallas, and San Jose** are the top 3 cities by revenue, enabling targeted regional marketing strategies
- **United States** accounts for nearly **70%** of all orders, confirming it as the dominant market across all years
- Avg Discount % of **7.4%** across categories is consistent, suggesting a uniform pricing strategy with minimal aggressive discounting
- Order status breakdown shows majority of orders are **Delivered**, reflecting strong fulfillment performance

---

### How to Use

- Download the `.pbix` file
- Open in **Power BI Desktop** (free download from Microsoft)
- Use the **Category** slicer to filter by product type
- Use the **Country** slicer to drill down by geography
- Use the **Order Status** slicer to analyze fulfillment patterns
- Use the **Year** slicer to track year-on-year performance
- Hover over charts for detailed tooltips

---

### Dataset

- **Source:** [Kaggle — Amazon Sales Dataset](https://www.kaggle.com/datasets/rohiteng/amazon-sales-dataset)
- **Rows:** 100,000+
- **Columns:** 15
- **Key Fields:** OrderID, OrderDate, ProductName, Category, Brand, Quantity, UnitPrice, Discount, TotalAmount, OrderStatus, PaymentMethod, City, State, Country

---

### 👤 Author

Anmol Tripathi
📧 anmoltripathi8329@gmail.com
