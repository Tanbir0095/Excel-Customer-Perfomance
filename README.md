# 📊 Sales Analysis Report using Excel Power Query & Power Pivot

This project focuses on analyzing monthly sales performance using Excel tools like **Power Query** and **Power Pivot**. The dataset includes customer, product, market, sales, and target information. The final report provides valuable insights into sales trends, actual vs. target performance, and regional breakdowns.

---

## 🗂️ Datasets Used

| Table Name         | Description                                                  |
|--------------------|--------------------------------------------------------------|
| `dim_customer`     | Contains customer-related information (ID, name, segment)    |
| `dim_market`       | Market data including country, region, and market categories |
| `dim_product`      | Product information like name, category, sub-category        |
| `fact_sales_monthly` | Monthly sales data including revenue, units sold, etc.    |
| `ns_target`        | Target data used for performance comparison                  |

---

## 🧹 Data Cleaning & Preparation

- Cleaned raw Excel files to ensure consistency
- Removed duplicates and handled null values
- Applied Power Query transformations:
  - Renamed and reordered columns
  - Merged relevant tables
  - Filtered data where necessary
  - Changed data types for accuracy

---

## ⚙️ Power Pivot Model

- Established relationships between fact and dimension tables
- Created calculated measures (e.g., `Total Sales`, `Sales vs Target`, `Growth %`)
- Created KPIs to track performance metrics
- Enabled time intelligence for monthly/yearly comparisons

---

## 📈 Report Highlights

- **Customer Performance**: Analysis of customer-wise sales contribution and segmentation
- **Market vs Target**: Comparison of actual sales vs targets across different markets
- **Top 10 Products**: Highest-performing products based on total sales
- **Division Report**: Sales analysis broken down by divisions or business units
- **New Arrival Products**: Performance tracking of newly launched products
- **Top 5 Countries**: Countries with the highest sales figures

---

## 🛠️ Tools Used

- Microsoft Excel
  - Power Query
  - Power Pivot
  - Pivot Tables and Charts
- Data Modeling (Star Schema)

---







-_
