# 📊 Sales & Revenue Dashboard — Power BI

## 📌 Project Overview

The **Sales & Revenue Dashboard** is an interactive business intelligence project developed using **Microsoft Power BI**. It analyzes sales performance, revenue, profit, quantity sold, products, categories, and regions through interactive KPI cards and visualizations.

The dashboard helps users quickly understand overall business performance and identify important sales and profitability trends.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall sales performance.
- Track total revenue and profit.
- Monitor total quantity sold.
- Analyze sales trends over time.
- Compare sales across regions.
- Compare sales across product categories.
- Identify product-level sales performance.
- Analyze profit across categories.
- Create an interactive and easy-to-understand business dashboard.

---

## 🛠️ Technologies & Tools Used

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel / CSV**
- **GitHub**

---

## 📂 Dataset

The project uses a sales dataset containing the following columns:

| Column | Description |
|---|---|
| Date | Date of the sales transaction |
| Region | Region where the sale occurred |
| Product | Product sold |
| Salesperson | Salesperson responsible for the sale |
| Units_Sold | Number of units sold |
| Unit_Price | Price per unit |
| Category | Product category |
| Revenue | Revenue generated |
| Cost | Cost associated with the sale |
| Profit | Profit generated |

---

## 🧹 Data Cleaning & Preparation

The dataset was cleaned and prepared before creating the dashboard.

### Data cleaning steps included:

1. Loaded the CSV dataset into Power BI.
2. Opened the dataset in **Power Query**.
3. Checked column names and data types.
4. Verified date and numerical columns.
5. Checked for duplicate records.
6. Used **Keep Duplicates** to verify duplicate rows.
7. The duplicate check returned **0 rows**.
8. Verified that the dataset was suitable for analysis.
9. Loaded the cleaned data into Power BI.

---

## 📐 DAX Measures

The following DAX measures were created for the dashboard.

### 1. Total Sales

```DAX
Total Sales = SUM(Sales[Revenue])
```
Calculates the total revenue generated from all sales transactions.

### 2. Total Profit
```DAX
Total Profit = SUM(Sales[Profit])
```
Calculates the total profit generated from sales.

### 3. Total Quantity

```DAX
Total Quantity = SUM(Sales[Units_Sold])
```
Calculates the total number of units sold.

### 4. Average Sales

```DAX
Average Sales = AVERAGE(Sales[Revenue])
```
Calculates the average revenue per sales transaction.

### 5. Profit Margin

```DAX
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```
Calculates profit as a percentage of total sales.

## 📊 Dashboard KPIs

The dashboard contains five main KPI cards:

KPI	Value
Total Profit	5.14M
Total Sales	20.40M
Total Quantity	19K
Average Sales	10.82K
Profit Margin	25.21%

These KPIs provide a quick overview of the company's overall sales and profitability.

## 📈 Dashboard Visualizations

The dashboard contains the following visualizations:

1. KPI Cards

Displays:

Total Profit
Total Sales
Total Quantity
Average Sales
Profit Margin

2. Sales Trend Over Time

A line chart showing how total sales change over time.

X-axis: Date
Y-axis: Total Sales

3. Sales by Category

A column chart comparing total sales across different product categories.

X-axis: Category
Y-axis: Total Sales

4. Sales by Region

A chart comparing total sales across different regions.

X-axis: Region
Y-axis: Total Sales

5. Sales by Product

A bar chart comparing sales performance across products.

Y-axis: Product
X-axis: Total Sales

6. Profit by Category

A column chart comparing total profit across product categories.

X-axis: Category
Y-axis: Total Profit

## 🔍 Key Business Insights

The dashboard can be used to identify:

Overall sales and revenue performance.
Overall profitability.
Changes in sales over time.
High-performing product categories.
Strong and weak-performing regions.
Products generating higher sales.
Categories generating higher profits.
The relationship between sales and profitability.

## 🧪 Testing & Validation

The dashboard was tested after development to ensure that all components were functioning correctly.

Testing Checklist
✅ KPI cards verified
✅ Sales Trend chart verified
✅ Sales by Category verified
✅ Sales by Region verified
✅ Sales by Product verified
✅ Profit by Category verified
✅ DAX measures verified
✅ Visual interactions verified
✅ Data labels verified
✅ Titles verified
✅ Axis settings verified
✅ Alt text verified
✅ Dashboard presentation verified

All dashboard components were checked and cleared successfully.

## 📁 Project Structure
Sales-Revenue-Dashboard/
│
├── README.md
├── .gitignore
├── Sales_Revenue_Dashboard.pbix
└── sales_data.csv

File names may vary depending on the final names used in the GitHub repository.

## 🚀 How to Use the Dashboard
Download the .pbix Power BI file.
Open the file using Microsoft Power BI Desktop.
Review the KPI cards.
Explore the sales trend over time.
Analyze sales by region, category, and product.
Review profit by category.
Use the interactive visual selections to explore the data.

## 📌 Project Workflow

The project was completed using the following workflow:

1. Collect Dataset
        ↓
2. Clean Data
        ↓
3. Load Data into Power BI
        ↓
4. Create DAX Measures
        ↓
5. Build Interactive Dashboard
        ↓
6. Test & Present

## 🎓 Skills Demonstrated

This project demonstrates practical knowledge of:

Data Cleaning
Data Preparation
Power Query
Data Visualization
Microsoft Power BI
DAX
KPI Development
Business Intelligence
Interactive Dashboard Development
Data Analysis
Business Reporting
GitHub Project Management

## 💡 Business Value

The dashboard converts raw sales data into meaningful business information.

It enables decision-makers to quickly monitor sales and profitability, compare different business segments, identify high-performing areas, and use data-driven insights to support business decisions.

## 👨‍💻 Author

Yash Sri

## 🎯 Career Focus

Aspiring Data Analyst with practical experience in Python, SQL, Power BI, data visualization, and machine learning projects.