# FNP-Sales-Analysis 📊

## Project Overview

This project focuses on analyzing FNP (Ferns N Petals) sales data using Microsoft Excel. The objective is to identify sales trends, customer purchasing behavior, product performance, and revenue patterns through an interactive dashboard. The insights generated help businesses make informed decisions and improve overall performance.

---

## Project Workflow

```mermaid
flowchart TD
A[Raw Dataset] --> B[Data Cleaning]
B --> C[Data Preprocessing]
C --> D[Pivot Tables & Analysis]
D --> E[Charts & KPIs]
E --> F[Interactive Dashboard]
F --> G[Business Insights & Recommendations]
```

---

## Dataset Used

Files included in this repository:

- customers.csv
- orders.csv
- products.csv
- project_fnp.xlsx

Dataset Link:
https://github.com/OmkarTatkare/FNP-Sales-Analysis/blob/main/project_fnp.xlsx

---

## Dataset Description

| Column Name | Description |
|------------|-------------|
| Order_ID | Unique identifier for each order |
| Customer_ID | Unique customer identifier |
| Order_Date | Date when the order was placed |
| Delivery_Date | Date when the order was delivered |
| Product_Name | Name of the product purchased |
| Category | Product category |
| Occasion | Occasion associated with the purchase |
| City | Customer city |
| Quantity | Quantity ordered |
| Revenue | Revenue generated from the order |

---

## Tools & Technologies Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- Conditional Formatting
- Data Validation
- Dashboard Design
- Lookup Functions (VLOOKUP/XLOOKUP)

---

## Repository Structure

```text
FNP-Sales-Analysis/
│
├── README.md
├── dashboard.png
├── customers.csv
├── orders.csv
├── products.csv
└── project_fnp.xlsx
```

---

## Business Questions (KPIs)

- What is the total number of orders?
- What is the total revenue generated?
- What is the average customer spending?
- What is the average order-delivery time?
- Which occasions generate the highest revenue?
- Which months contribute the highest sales?
- Which cities generate the highest number of orders?
- Which product categories contribute maximum revenue?
- Which products generate the highest revenue?
- What are the peak order hours?

---

## Data Cleaning & Preprocessing

- Verified dataset for missing values and inconsistencies.
- Removed duplicate records.
- Standardized date formats.
- Checked data consistency across all datasets.
- Validated revenue and order values.
- Prepared data for Pivot Table analysis and dashboard creation.

---

## Dashboard Features

### KPI Cards
- Total Orders
- Total Revenue
- Average Customer Spend
- Average Order Delivery Time

### Interactive Filters
- Order Date
- Delivery Date
- Occasion

### Dynamic Visualizations
- Revenue by Occasion
- Revenue by Month
- Revenue by Category
- Revenue by Hour
- Top Products by Revenue
- Top Cities by Orders

---

## Dashboard

![FNP Dashboard](dashboard.png)

---

## Key Insights

- Anniversary and Raksha Bandhan generated the highest revenue among all occasions.
- February and August recorded peak sales performance.
- Colors and Soft Toys contributed the highest category revenue.
- Peak order activity was observed during evening hours.
- Imphal and Kavali ranked among the top-performing cities based on order volume.
- Average customer spending was approximately ₹3,520.
- The dashboard enables easy comparison of sales trends across occasions, months, and product categories.

---

## Final Conclusion

The interactive Excel dashboard provides valuable insights into customer purchasing behavior, seasonal sales patterns, and product performance. By leveraging Pivot Tables, Pivot Charts, KPI Cards, and dynamic filtering, businesses can identify growth opportunities, optimize inventory planning, and improve marketing strategies through data-driven decision-making.

---

## Author

**Omkar Tatkare**

GitHub: https://github.com/OmkarTatkare
