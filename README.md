# 📊 Restaurant Performance Dashboard

This project is a **Business Analytics portfolio** dashboard built using **Tableau Public**, designed to analyze the performance of a restaurant over a 3-month period using sales, customer, and feedback data.

[🔗 View the Interactive Dashboard on Tableau Public](https://public.tableau.com/views/Restaurant_dashboard_17444671317480/Dashboard1)

---

## 📌 Project Overview

The **Restaurant Performance Dashboard** provides a high-level summary of key performance indicators (KPIs) to help stakeholders understand sales trends, customer satisfaction, and staff performance.

### ✅ Business Questions Answered:

- How many orders and customers did the restaurant serve?
- What is the total revenue generated?
- What’s the average customer rating?
- Which menu items are top-selling?
- Which waiter contributed most to the revenue?
- What do customer rating trends reveal?

---

## 💾 Data Source

The dataset (`restaurant_dashboard.xlsx`) includes:
- Order details
- Revenue information
- Customer feedback with ratings
- Menu item performance
- Waiter assignments

---

## 🧹 Data Cleaning & Preparation

Data cleaning was performed in **Excel** before importing to Tableau. Steps included:

1. **Date Formatting**: Standardized all date fields for proper time-series analysis.
2. **Revenue Calculation**: Ensured revenue values were numeric and summed correctly by order.
3. **Customer Ratings**: Cleaned and filtered out any null or invalid rating entries.
4. **Waiter Attribution**: Linked orders to corresponding waiters to calculate revenue per staff.
5. **Menu Item Aggregation**: Grouped and counted sales per menu item to identify top performers.
6. **Removed Duplicates**: Checked for and eliminated any duplicate order records.
7. **Created a Star Schema** (optional enhancement): Structured data into fact and dimension tables (Orders, Customers, Waiters, Items) for scalability.

---

## 📊 Key Metrics

| Metric             | Value         |
|--------------------|---------------|
| Total Orders       | 100           |
| Total Revenue      | $4,657.59     |
| Average Rating     | 3.9           |
| Total Customers    | 30            |

---

## 📈 Dashboard Features

- **Daily Revenue Trend** (with outlier detection)
- **Waiter Revenue Contribution** (bubble chart)
- **Top Selling Menu Items** (horizontal bar chart)
- **Customer Review Rating Distribution**
- **Interactive, clean UI built in Tableau**

---

## 🛠️ Tools & Technologies

- **Tableau Public** – for data visualization
- **Excel** – for data cleaning and transformation
- **Canva/Figma (optional)** – for visual design tweaks

---

## 📥 How to Use

1. Download the Excel dataset from this repo.
2. Open the Tableau workbook or access the [public link](https://public.tableau.com/views/Restaurant_dashboard_17444671317480/Dashboard1).
3. Explore KPIs, trends, and drill down into customer feedback.

---

## 💡 Insights

- **Caesar Salad** was the best-selling item with 90 orders.
- Majority of customers rated the restaurant 3 stars.
- **Priya** and **Luis** generated the most revenue among waitstaff.
- Revenue patterns show fluctuation with occasional spikes in daily earnings.

---

## 📁 Files in this Repo

- `restaurant_dashboard.xlsx` – cleaned dataset
- `Restaurant Performance Dashboard.png` – screenshot of the final dashboard
- `README.md` – project overview

---

## 📣 Author

**Lauhith Natarajan** – Business Analytics Enthusiast  

