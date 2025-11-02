# 🍫 Chocolate Sales Analysis Dashboard 2023 – Power BI Project by Muhammad Azeem

## 📊 Project Overview

This is my **first Power BI project**, created as part of my Data Analyst learning journey.
It represents an **end-to-end analysis process** — from sourcing and cleaning data in Excel to building an interactive Power BI dashboard with business insights.

The dataset represents chocolate sales records collected from GitHub, cleaned in Excel, and visualized in Power BI.

---

## 🧾 Dataset Details

* **Source:** Public dataset from GitHub
* **Preparation:** Excel (data cleaning, formatting, and KPI setup)
* **Visualization:** Power BI (interactive dashboard and DAX measures)

---

## ⚙️ Tools & Technologies

* **Microsoft Excel** → Data cleaning & preprocessing
* **Power BI Desktop** → DAX measures, visuals, and interactivity
* **GitHub** → Project hosting and portfolio sharing

---

## 💵 Currency Used

* **Currency:** USD ($)
  *(Chosen for international portfolio visibility. Local dashboards can use PKR ₨ as needed.)*

---

## 📈 Key Insights

1. **Total Sales:** $27,990,857
2. **Delivery Rate:** 83%
3. **Top 2 Sales Representatives** contribute **~15%** to total revenue
4. **Sales Trend:** Strong performance in mid-year months
5. **Order Status:** 83% of all orders successfully delivered

---

## 🎨 Dashboard Design

* Clean beige theme with chocolate color accents (#6B4226, #D7C7AD, #F8F4E3)
* Rounded visuals (corner radius = 12)
* KPI cards for Total Sales, Orders, and Delivery Rate
* Donut and bar charts for category-based breakdowns
* Line chart for monthly sales trends

---

## 💡 Problem Statement

The chocolate company wanted to track **sales performance and delivery efficiency** across products and salespersons.
They needed to identify:

* Which products sell best
* Which salespersons generate most revenue
* Delivery performance and order status
* Overall revenue and sales trends over time

---

## 🧩 Case Study – Chocolate Sales Dashboard 2023

### 🧾 Dataset Overview

The dataset contained **4,998 rows and 7 columns**:
`Date`, `Product`, `Boxes`, `Amount`, `Salesperson`, `Country`, and `Order Status`.
It was cleaned in Excel before importing into Power BI.

---

### ⚙️ Process & Steps

#### 1️⃣ Data Cleaning (Excel)

* Removed null values & duplicates
* Verified numeric columns (Boxes, Amount)
* Saved cleaned data for Power BI import

#### 2️⃣ Data Modeling (Power BI)

Created key **DAX measures**:

```
Total Sales = SUM(Amount)
Total Boxes = SUM(Boxes)
Total Orders = COUNTROWS(Data)
Delivery Rate = DIVIDE([Delivered Orders], [Total Orders])
Average Order Value = DIVIDE(SUM(Amount), COUNTROWS(Data))
```

#### 3️⃣ Dashboard Design

* Used a chocolate-themed color palette
* Added visuals:

  * Line Chart → Monthly Sales Trend
  * Donut Chart → Order Status Breakdown
  * Bar Chart → Top 5 Products by Sales
  * Horizontal Bar → Sales by Salesperson
  * KPI Cards → Sales, Orders, Delivery Rate

---

## 📊 Key Insights

* **Delivered Orders:** 83% (strong fulfillment rate)
* **Cancelled Orders:** 4.5% (needs improvement)
* **Top 2 Salespersons:** Generated 15% of revenue
* **Best-Selling Product:** *Choco Coated Almonds*
* **Peak Sales Months:** *April–July*

---

## 📸 Dashboard Screenshots

### KPI Overview

![KPI Overview](Screenshots/top_kpis.png)

### Sales Trend & Order Status

![Sales Trend](Screenshots/sales_trend_status.png)

### Top 5 Products & Salesperson

![Sales by Person](Screenshots/sales_by_person.png)

### Full Dashboard Layout

![Full Dashboard](Screenshots/dashboard_overview.png)

---

## 🏁 Outcome

This dashboard provides a **complete business overview**, helping management track:

* Sales performance
* Order fulfillment
* Product and salesperson efficiency
* Seasonal revenue trends

It demonstrates **practical Power BI dashboard design, data cleaning, and analysis skills**.

---

## 📂 Files Included

| File Type                                | Description                      |
| ---------------------------------------- | -------------------------------- |
| 📘 `Chocolate_Sales_2023.xlsx`           | Cleaned Excel dataset            |
| 📊 `Chocolate_Sales_Dashboard_2023.pbix` | Final Power BI dashboard         |
| 🖼️ `Screenshots/`                       | Dashboard preview images         |
| 📄 `README.md`                           | Project documentation & insights |

---

## 🧠 Author

**Muhammad Azeem**
*Data Analyst | Power BI Developer*
📍 Pakistan
🔗 [LinkedIn Profile](https://www.linkedin.com/in/muhammad-azeem-06b799231/)
