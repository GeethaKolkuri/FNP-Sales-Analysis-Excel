# 🎁 FNP Sales Analysis – Excel

## 📊 Project Overview

This project focuses on analyzing FNP sales data using Microsoft Excel.

The objective is to analyze customer orders, revenue, delivery performance, product categories, occasions, order timing, monthly sales, and city-level order performance.

The project combines customer, order, and product datasets and uses Excel data analysis techniques, PivotTables, Pivot Charts, slicers, timelines, KPI cards, and an interactive dashboard to generate meaningful business insights.

The complete Excel analysis and dashboard are available in:

`5th_ excel_DashB.xlsx`

The supporting datasets are:

`customers.csv`

`orders.csv`

`products.csv`

---

## 🎯 Objectives

- Analyze total orders and total revenue.
- Analyze average customer spending.
- Analyze average order-to-delivery time.
- Analyze revenue by occasion.
- Analyze revenue by product category.
- Analyze revenue by order hour.
- Analyze monthly revenue trends.
- Identify top products by revenue.
- Identify cities with the highest number of orders.
- Analyze customer and product information.
- Create calculated fields for time and delivery analysis.
- Build an interactive Excel dashboard.
- Use slicers and timelines for dynamic filtering.
- Generate business insights from sales data.

---

## 🗂️ Datasets

This project uses three supporting datasets.

### 1. `customers.csv`

The customer dataset contains:

- Customer ID
- Customer Name
- City
- Contact Number
- Email
- Gender
- Address

The dataset contains:

- **100 customers**
- **7 columns**

---

### 2. `orders.csv`

The orders dataset contains:

- Order ID
- Customer ID
- Product ID
- Quantity
- Order Date
- Order Time
- Delivery Date
- Delivery Time
- Location
- Occasion

The dataset contains:

- **1,000 orders**
- **10 columns**

The Excel project further derives analytical fields including:

- Month Name
- Hour of Order Time
- Order-to-Delivery Difference
- Hour of Delivery Time
- Price
- Revenue
- Day Name of Order Date

---

### 3. `products.csv`

The products dataset contains:

- Product ID
- Product Name
- Category
- Price
- Occasion
- Description

The dataset contains:

- **70 products**
- **6 columns**

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- PivotTables
- Pivot Charts
- Slicers
- Timeline Filters
- Excel Formulas
- Data Transformation
- Data Aggregation
- Data Analysis
- Data Visualization
- Interactive Dashboard

---

## 🔍 Data Preparation & Transformation

The project combines customer, order, and product information to create a structured sales-analysis workflow.

### 1. Customer Data

Customer information is used to provide customer-level details such as:

- Customer name
- Gender
- City
- Contact information
- Address

### 2. Order Data

Order-level information is used to analyze:

- Order volume
- Quantity sold
- Order dates
- Order times
- Delivery dates
- Delivery times
- Locations
- Occasions

### 3. Product Data

Product information is used to analyze:

- Product names
- Product categories
- Product prices
- Product occasions

### 4. Derived Fields

The Excel analysis contains additional calculated fields to support business analysis:

- `Month Name`
- `Hour (Order Time)`
- `diff_order_delivery`
- `Hour (Delivery time)`
- `Revenue`
- `Day Name(Order Date)`

These fields allow the dashboard to analyze sales performance by time, delivery duration, and revenue.

---

## 📊 Overall Sales Analysis

The complete orders dataset contains:

- **1,000 orders**
- **3,045 units**
- **₹35,20,984 total revenue**
- **5.53 days average order-to-delivery time**

The average revenue per order across the complete dataset is approximately:

**₹3,520.98**

---

## 🎛️ Dashboard Filter Analysis

The dashboard contains interactive filters for:

### Order Date

A timeline filter allows users to analyze sales across different order-date periods.

### Delivery Date

A delivery-date timeline allows users to analyze delivery-related information by period.

### Occasion

The dashboard provides filtering for:

- All Occasions
- Anniversary
- Birthday
- Diwali
- Holi
- Raksha Bandhan
- Valentine's Day

The dashboard screenshot shows the following occasions selected:

- Birthday
- Diwali
- Holi
- Raksha Bandhan

This filtered selection contains:

- **556 Total Orders**
- **₹19,28,244 Total Revenue**
- **5.53057554 days Average Order-to-Delivery Time**
- **₹3,468.06 Average Customer Spend**

---

## 💰 Revenue by Occasion

Revenue was analyzed across different occasions.

For the complete dataset:

| Occasion | Orders | Revenue |
|---|---:|---:|
| Anniversary | 205 | ₹7,08,740 |
| Holi | 180 | ₹5,74,682 |
| Birthday | 149 | ₹4,08,194 |
| Raksha Bandhan | 132 | ₹6,31,585 |
| All Occasions | 126 | ₹4,58,664 |
| Valentine's Day | 113 | ₹3,27,? |
| Diwali | 95 | ₹3,13,783 |

The dashboard provides an interactive way to compare revenue across these occasions.

The selected dashboard view highlights:

- Birthday
- Diwali
- Holi
- Raksha Bandhan

Together, these selected occasions generate:

**₹19,28,244 revenue**

---

## 📦 Revenue by Category

The product dataset contains seven major categories.

Revenue across the complete order dataset is:

| Category | Revenue |
|---|---:|
| Colors | ₹10,05,645 |
| Soft Toys | ₹7,40,831 |
| Sweets | ₹7,33,842 |
| Cake | ₹3,29,862 |
| Raksha Bandhan | ₹2,97,372 |
| Plants | ₹2,12,281 |
| Mugs | ₹2,01,151 |

**Colors** is the highest-revenue category in the complete dataset.

---

## ⏰ Revenue by Hour

Revenue was analyzed according to the hour at which orders were placed.

The dashboard contains a line chart titled:

**Revenue by Hour (Order Time)**

This visualization helps identify:

- High-revenue ordering periods
- Low-revenue ordering periods
- Changes in customer ordering behavior throughout the day

The analysis can be used to understand customer ordering patterns and identify periods of higher sales activity.

---

## 📅 Revenue by Month

The dashboard contains a monthly revenue trend visualization covering all twelve months.

Complete-dataset monthly revenue includes:

| Month | Revenue |
|---|---:|
| January | ₹95,468 |
| February | ₹7,04,509 |
| March | ₹5,11,823 |
| April | ₹1,40,393 |
| May | ₹1,50,346 |
| June | ₹1,57,913 |
| July | ₹1,35,826 |
| August | ₹7,37,389 |
| September | ₹1,36,938 |
| October | ₹1,51,619 |
| November | ₹4,49,169 |
| December | ₹1,49,591 |

The highest complete-dataset monthly revenue occurs in:

**August – ₹7,37,389**

February is the second-highest month with:

**₹7,04,509**

---

## 🏆 Top 5 Products by Revenue

The dashboard contains a Top 5 Products by Revenue visualization.

Based on the complete dataset, the highest-revenue products include:

| Product | Revenue |
|---|---:|
| Magnam Set | ₹1,21,905 |
| Quia Gift | ₹1,14,476 |
| Dolores Gift | ₹1,06,624 |
| Harum Pack | ₹1,01,556 |
| Deserunt Box | ₹97,665 |

The **Magnam Set** is the highest-revenue product in the complete dataset.

---

## 🏙️ Top Cities by Orders

The dashboard includes a Top 10 Cities by Orders visualization.

Based on the complete dataset, the highest order counts include:

| City | Orders |
|---|---:|
| Ghaziabad | 9 |
| Bareilly | 9 |
| Bhilai | 8 |
| Darbhanga | 7 |
| Sirsa | 7 |
| Bulandshahr | 7 |
| Ozhukarai | 7 |
| Varanasi | 7 |
| Alwar | 7 |
| Satara | 7 |

The dashboard uses city-level order counts to identify locations with higher order activity.

---

## 🚚 Delivery Performance

The project analyzes the difference between order date and delivery date using:

`diff_order_delivery`

Across the complete order dataset:

- **Average delivery time: 5.53 days**
- **Minimum delivery time: 1 day**
- **Maximum delivery time: 10 days**

The dashboard displays average order-to-delivery time as a KPI.

For the selected dashboard occasions:

**Average Order-to-Delivery Time = 5.53057554 days**

This metric provides an overview of delivery performance for the selected sales segment.

---

## 📊 Dashboard KPIs

The Excel dashboard contains four main KPI cards.

### Total Orders

For the selected dashboard filters:

**556**

### Total Revenue

For the selected dashboard filters:

**₹19,28,244.00**

### Average Order-Time Delivery

For the selected dashboard filters:

**5.53057554 days**

### Average Customer Spend

For the selected dashboard filters:

**₹3,468.06**

These KPIs update according to the selected dashboard filters.

---

## 📈 Dashboard Visualizations

The dashboard contains the following visualizations:

### Revenue by Occasions

A column chart compares revenue across different occasions.

### Revenue by Category

A column chart compares revenue across product categories.

### Revenue by Hour

A line chart displays revenue across different order hours.

### Revenue by Months

A line chart displays monthly revenue trends.

### Top 5 Products by Revenue

A column chart identifies the highest-revenue products.

### Top 10 Cities by Orders

A column chart compares order counts across the leading cities.

---

## 📸 Dashboard Screenshot

The completed Excel dashboard is represented in:

`5th excel.jpg`

![FNP Sales Analysis Dashboard](<5th excel.jpg>)

The dashboard contains:

- Total Orders KPI
- Total Revenue KPI
- Average Order-Time Delivery KPI
- Average Customer Spend KPI
- Revenue by Occasions
- Revenue by Category
- Revenue by Hour
- Revenue by Months
- Top 5 Products by Revenue
- Top 10 Cities by Orders
- Order Date timeline
- Delivery Date timeline
- Occasion slicer

---

## 💡 Key Takeaways

- The complete dataset contains **1,000 orders**.
- The complete dataset contains **3,045 units sold**.
- Complete-dataset revenue is **₹35,20,984**.
- The average order-to-delivery time is **5.53 days**.
- The dashboard-selected occasions contain **556 orders**.
- The selected occasions generate **₹19,28,244 revenue**.
- The selected dashboard view has an average customer spend of **₹3,468.06**.
- **Colors** is the highest-revenue category with **₹10,05,645**.
- **Magnam Set** is the highest-revenue product with **₹1,21,905**.
- **August** has the highest complete-dataset monthly revenue with **₹7,37,389**.
- **February** has the second-highest monthly revenue with **₹7,04,509**.
- Ghaziabad and Bareilly have the highest complete-dataset order counts with **9 orders each**.
- The dashboard provides interactive filtering through order-date, delivery-date, and occasion controls.

---

## 🧠 Business Insights

The analysis provides a comprehensive view of FNP sales performance across **customers, products, occasions, categories, time, delivery performance, and locations**.

The complete dataset shows that **Colors** is the highest-revenue category, while **Magnam Set** is the highest-revenue product.

Sales also vary considerably by month, with **August and February** generating the highest complete-dataset revenue.

Occasion-based analysis is particularly useful for an FNP-style business because sales can vary depending on gifting occasions. The dashboard allows users to isolate occasions such as Birthday, Diwali, Holi, and Raksha Bandhan and evaluate their combined performance.

Delivery performance is also incorporated into the dashboard through average order-to-delivery time, allowing sales performance to be considered alongside operational delivery performance.

The dashboard can support:

- Occasion-based marketing
- Product performance analysis
- Inventory planning
- Revenue forecasting
- Customer spending analysis
- Delivery performance monitoring
- City-level sales analysis
- Time-based sales planning
- Product category strategy

---

## 🚀 Skills Demonstrated

- Microsoft Excel
- Data Analysis
- Data Preparation
- Data Transformation
- PivotTables
- Pivot Charts
- Slicers
- Timeline Filters
- KPI Development
- Sales Analysis
- Revenue Analysis
- Customer Analysis
- Product Analysis
- Category Analysis
- Occasion Analysis
- Time-Series Analysis
- Delivery Performance Analysis
- City-Level Analysis
- Data Visualization
- Interactive Dashboard Development
- Business Insight Generation
- Data Storytelling

---

## 📁 Repository Structure

```text
FNP-Sales-Analysis-Excel/
│
├── README.md
│
├── Dataset/
│   ├── customers.csv
│   ├── orders.csv
│   └── products.csv
│
├── Project/
│   └── 5th_ excel_DashB.xlsx
│
└── Dashboard/
    └── 5th excel.jpg
```
📌 Conclusion

This project demonstrates a complete Excel-based FNP sales analysis workflow, starting with customer, order, and product datasets and continuing through data preparation, calculated fields, PivotTables, Pivot Charts, slicers, timeline filters, KPI development, and interactive dashboard creation.

The analysis examines revenue, orders, customer spending, delivery performance, occasions, product categories, order timing, monthly sales, products, and city-level order activity.

The complete order dataset contains 1,000 orders, 3,045 units, and ₹35,20,984 in revenue, with an average order-to-delivery time of 5.53 days.

The dashboard also provides a focused analysis of selected occasions. For the displayed selection of Birthday, Diwali, Holi, and Raksha Bandhan, there are 556 orders, generating ₹19,28,244 in revenue, with an average order-to-delivery time of 5.53057554 days and an average customer spend of ₹3,468.06.

Overall, this project demonstrates practical skills in Microsoft Excel, data analysis, data transformation, PivotTables, Pivot Charts, slicers, timeline filters, KPI development, sales analysis, customer analysis, product analysis, delivery analysis, data visualization, interactive dashboard development, and business insight generation.
