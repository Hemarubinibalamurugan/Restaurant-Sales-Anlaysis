# 🍽️ Restaurant Sales Analysis Dashboard | Power BI

## 📌 Project Overview

The Restaurant Sales Analysis Dashboard is an interactive business intelligence solution developed using Microsoft Power BI. The project analyzes restaurant sales data to identify sales trends, customer behavior, branch performance, menu item performance, and operational insights. The dashboard enables restaurant management to make informed, data-driven decisions that improve sales, customer satisfaction, and overall business performance.

---

# 🎯 Project Objectives

- Analyze overall restaurant sales performance.
- Monitor monthly and daily sales trends.
- Compare weekend and weekday sales.
- Evaluate branch-wise sales performance.
- Identify best-selling and low-performing menu items.
- Analyze customer ratings and order types.
- Generate actionable business insights for decision-making.

---

# ❓ Problem Statements

## Descriptive Analytics
- What is the overall sales performance of the restaurant?
- Which branch generates the highest sales?
- Which order type contributes the highest revenue?

## Diagnostic Analytics
- Why are weekend sales higher than weekday sales?
- Why is the Lincoln Park branch performing below average?
- Why do some menu items perform better than others?

## Predictive Analytics
- Which months are expected to generate higher sales in the future?
- Which menu items are likely to experience increased customer demand?

## Prescriptive Analytics
- What strategies can improve the performance of underperforming branches?
- How can inventory, staffing, and marketing be optimized to maximize restaurant sales?

---

# 📂 Dataset Information

The dataset contains restaurant transaction records, including:

- Order ID
- Order Date
- Restaurant Location
- Order Type
- Category
- Menu Item
- Quantity
- Order Total
- Customer Rating

---

# 🛠️ Data Cleaning

- Removed duplicate records
- Checked missing values
- Standardized column names
- Corrected data types
- Formatted date columns
- Prepared data for analysis

---

# 📊 Dashboard KPIs

- Total Sales
- Total Orders
- Total Quantity Sold
- Average Customer Rating
- Average Order Value

---

# 📈 Dashboard Visualizations

- Monthly Sales Trend
- Weekend vs Weekday Sales
- Branch-wise Sales Analysis
- Order Type Analysis
- Customer Rating Analysis
- Category-wise Sales
- Top 10 Best-Selling Menu Items
- Restaurant Location Analysis

---

# 📌 DAX Measures Used

```DAX
Total Sales =
SUM('Restaurant Sales'[Order Total])

Total Orders =
DISTINCTCOUNT('Restaurant Sales'[Order ID])

Total Quantity Sold =
SUM('Restaurant Sales'[Quantity])

Average Rating =
AVERAGE('Restaurant Sales'[Customer Rating])

Average Order Value =
DIVIDE([Total Sales],[Total Orders],0)
```

---

# 📊 Key Business Insights

- Weekend sales are significantly higher than weekday sales, indicating increased customer demand during weekends.
- Monthly sales analysis shows noticeable fluctuations, with certain months generating higher revenue than others.
- The Lincoln Park branch is performing below the overall average and requires strategic improvements.
- Dine-in orders contribute the highest share of total restaurant sales compared to Takeaway and Delivery.
- Best-selling menu items generate the highest revenue and should be prioritized in inventory management.
- Low-performing menu items require promotional campaigns or menu optimization to improve sales.
- Branch-wise sales analysis highlights differences in performance, helping identify high-performing and underperforming locations.
- Customer rating analysis indicates that improving service quality can enhance customer satisfaction and customer retention.
- Sales trends provide valuable insights for forecasting future demand and planning business operations.
- High-demand menu items should be stocked adequately to avoid inventory shortages during peak periods.
- Additional staff should be allocated during weekends to efficiently manage increased customer traffic.
- Targeted marketing campaigns should be implemented to improve sales in low-performing branches.
- Regular analysis of customer feedback can help improve food quality, service efficiency, and the overall dining experience.
- Data-driven decision-making can improve restaurant performance, maximize revenue, and support sustainable business growth.

---

# 💼 Business Recommendations

- Increase staffing during weekends to manage higher customer traffic.
- Focus marketing campaigns on low-performing branches.
- Promote low-selling menu items through discounts and combo offers.
- Maintain sufficient inventory for high-demand products.
- Improve customer service to increase customer ratings.
- Continuously monitor monthly sales trends for better forecasting.

---

# 🛠️ Tools & Technologies

- Microsoft Power BI
- Microsoft Excel
- Power Query
- DAX
- Data Modeling

---

# 🚀 Business Outcome

This dashboard enables restaurant management to monitor sales performance, identify business opportunities, optimize operations, improve customer satisfaction, and make strategic decisions that drive sustainable business growth.

---

# 👩‍💻 Author

**Hemarubini B**

Aspiring Data Analyst

### Skills
- Microsoft Excel
- Power BI
- SQL
- Python
- Data Visualization
- Data Analysis

---
⭐ If you found this project useful, please consider giving it a Star on GitHub!
