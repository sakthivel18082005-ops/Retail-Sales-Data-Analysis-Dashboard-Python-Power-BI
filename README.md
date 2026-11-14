# 📊 Retail Sales Data Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing online retail sales data to identify sales trends, understand product performance, and evaluate country-wise revenue.

The project follows an end-to-end data analytics workflow, including data cleaning, data preprocessing, Exploratory Data Analysis (EDA), and interactive dashboard development using Power BI.

## 🎯 Project Objectives

- Clean and preprocess raw retail sales data.
- Handle missing values and duplicate records.
- Identify and exclude cancellation transactions from positive-sales analysis.
- Calculate total revenue, total orders, units sold, and average order value.
- Analyze monthly sales trends.
- Identify the top 10 products by revenue.
- Compare sales performance across different countries.
- Develop an interactive Power BI dashboard.

## 📂 Dataset Description

**Dataset:** Online Retail Dataset

**Source:** UCI Machine Learning Repository

**Original Dataset Size:** 541,909 rows and 8 columns.

### Dataset Attributes

| Column | Description |
|---|---|
| InvoiceNo | Invoice number |
| StockCode | Product code |
| Description | Product description |
| Quantity | Number of products purchased |
| InvoiceDate | Date of transaction |
| UnitPrice | Price per unit |
| CustomerID | Customer identification number |
| Country | Customer's country |

## 🛠️ Technologies Used

- **Python** – Data processing and analysis
- **Google Colab** – Python development environment
- **Pandas** – Data cleaning and manipulation
- **Matplotlib** – Data visualization
- **Microsoft Power BI** – Interactive dashboard development
- **Microsoft Excel / CSV** – Dataset management

## 🧹 Data Cleaning and Preprocessing

The following operations were performed:

1. Loaded the Online Retail dataset.
2. Checked missing values and duplicate records.
3. Replaced missing product descriptions with `Unknown Product`.
4. Retained missing CustomerID values.
5. Removed duplicate records.
6. Converted columns into appropriate data types.
7. Identified cancellation transactions.
8. Filtered positive sales transactions by excluding cancellation invoices and non-positive quantities or prices.
9. Created a new column named `TotalSales`.

**Revenue Calculation:**

`TotalSales = Quantity × UnitPrice`

## 📈 Exploratory Data Analysis

The following analyses were performed:

- Total revenue analysis
- Total order analysis
- Product sales analysis
- Country-wise sales analysis
- Monthly sales trend analysis
- Customer purchasing analysis

## 📊 Key Performance Indicators

The complete positive-sales dataset produced the following results:

| KPI | Result |
|---|---:|
| Total Revenue | £10,642,110.80 |
| Total Orders | 19,960 |
| Total Units Sold | 5,572,420 |
| Average Order Value | £533.17 |

**Average Order Value Formula:**

`Average Order Value = Total Revenue / Total Orders`

## 📉 Power BI Dashboard

An interactive Retail Sales Dashboard was developed using Microsoft Power BI.

### Dashboard Features

1. **Total Revenue** – Displays overall sales revenue.
2. **Total Orders** – Displays the number of unique orders.
3. **Total Units Sold** – Displays the total quantity sold.
4. **Average Order Value** – Displays average revenue per order.
5. **Monthly Sales Trend** – Visualizes sales performance over time.
6. **Top 10 Products by Revenue** – Identifies the highest revenue-generating products.
7. **Country-wise Sales** – Compares sales across different countries.
8. **Date Slicer** – Filters sales within a selected date range.
9. **Country Slicer** – Filters dashboard results by country.

## 📁 Project Structure

```text
SWYNEX-Retail-Sales-Analysis/
│
├── dataset/
│   ├── Online Retail.xlsx
│   ├── Cleaned_Retail_Sales.csv
│   └── Retail_Sales_Analysis.csv
│
├── notebooks/
│   └── Retail_Sales_Analysis.ipynb
│
├── visualizations/
│
├── dashboard/
│   ├── Retail_Sales_Dashboard.pbix
│   └── Retail_Sales_Dashboard.pdf
│
├── report/
│   └── Retail_Sales_Analysis_Report.docx
│
└── README.md
```

## ▶️ How to Run the Project

### Step 1: Download the Dataset

Download the Online Retail dataset from the UCI Machine Learning Repository.

### Step 2: Open Google Colab

Upload the dataset and open the project notebook.

### Step 3: Perform Data Cleaning

Execute the Python cells to clean, preprocess, and prepare the retail sales dataset.

### Step 4: Perform Exploratory Data Analysis

Run the analysis and visualization cells to understand sales patterns.

### Step 5: Open Power BI

Import `Retail_Sales_Analysis.csv` into Microsoft Power BI Desktop.

### Step 6: Explore the Dashboard

Open `Retail_Sales_Dashboard.pbix` and interact with the KPI cards, charts, and slicers.

## 💡 Key Learnings

- Practical experience in data cleaning and preprocessing.
- Understanding missing values and duplicate records.
- Working with Python Pandas for data analysis.
- Performing Exploratory Data Analysis.
- Creating meaningful data visualizations.
- Developing interactive dashboards using Power BI.
- Understanding business insights from retail transaction data.

## 🏁 Conclusion

This project demonstrates how raw retail transaction data can be transformed into meaningful business insights through data cleaning, exploratory analysis, and interactive visualization.

The Power BI dashboard provides an effective way to monitor sales performance, identify top-performing products, and explore country-wise and monthly sales trends.

## 👨‍💻 Project Information

**Project:** Retail Sales Data Analysis

**Organization:** SWYNEX

**Domain:** Data Analytics

**Tools:** Python, Google Colab, Pandas, Matplotlib, Microsoft Power BI

---

⭐ If you find this project useful, feel free to explore the repository and its analysis.
