
# 📊 AdventureWorks – End-to-End Power BI Business Intelligence Solution

## 🔹 Project Overview

This project demonstrates an end-to-end **Enterprise Business Intelligence solution using Power BI**, built on the AdventureWorks dataset across multiple modules.

The objective was to explore how AdventureWorks can empower business users through:

* Data Modeling
* Self-Service BI
* Enterprise Reporting
* Dashboard Creation
* DirectQuery & Azure Integration
* Row-Level Security (RLS)
* Scheduled Refresh & Power BI Service Deployment

This project simulates a real-world BI implementation lifecycle — from raw data to published dashboard.

---

# 🧩 Project Architecture

**Data Sources Used:**

* AdventureWorksDW (SQL Database)
* AdventureWorksLT (SQL Database)
* Excel Files (Sales-Europe, Sales-North America, Country Code, Sales Data)
* Azure SQL Database (DirectQuery Mode)
* Wikipedia (State codes web data)
* Lans Transport Corp Excel Workbook
* Student Survey Dataset

---

# 🔹 Key Implementations

---

## 1️⃣ Data Import & Transformation (Power Query)

* Imported SQL Server and Excel data sources
* Reduced Excel file size and formatted tables
* Converted columns to correct data types (Date, Currency)
* Appended and merged tables
* Shaped and cleaned datasets
* Removed unnecessary columns
* Renamed fields for business clarity
* Combined multi-region sales data
* Merged country codes and state codes
* Applied data categorization (Address, City, Country etc.)

---

## 2️⃣ Data Modeling & Relationships

* Created Star Schema with Fact and Dimension tables
* Built multiple relationships:

  * OrderDateKey → DateKey (*:1 Active)
  * DueDateKey → DateKey
  * ShipDateKey → DateKey
* Configured Cross-filter directions (Single & Both)
* Managed Many-to-One relationships
* Deleted incorrect relationships
* Built hierarchical product category relationships

---

## 3️⃣ DAX Calculated Columns & Measures

### 🔸 Customer Intelligence

* IncomeStatus classification
* DaysSinceFirstPurchase
* FullName (Concatenation)
* Gender mapping (Male/Female)
* Marital Status mapping

### 🔸 Product Intelligence

* MainCategory column

### 🔸 Promotion Analysis

* PromotionLengthDays

### 🔸 Sales Intelligence

* Profit (UnitPrice - ProductStandardCost)
* LineTotal (OrderQty × ListPrice)
* TargetSales (2% increase measure)

---

## 4️⃣ Visualizations Created

### 📌 Sales Analytics

* Column Chart → Sales by Day of the Week
* Pie Chart → Sales by Calendar Quarter (Custom Color Coding)
* Map → Sales by Country
* Funnel → Sales by Commute Distance
* Gauge → Target Sales Tracking
* Stacked Bar → Sales by Main Category
* Donut → Sales Distribution
* Stacked Column → Top Selling Bikes
* Scatter Plot → Video Games vs Outdoor Sports
* Sand Dance Plot → Indoor vs Video Games
* Matrix → Outdoor Sports by Age
* Conditional Formatting (Color Logic Based on Value Ranges)

---

## 5️⃣ Advanced Features

### 🔹 Top N Filtering

* Top 10 products by SalesAmount

### 🔹 Constant Lines & Analytics Pane

* Sales Threshold lines

### 🔹 RLS (Row-Level Security)

* Restricted access based on User Mapping table
* Example: Rural-only access for specific users

### 🔹 DirectQuery (Azure SQL)

* Connected to Azure SQL Database using DirectQuery
* Created slicers and card visuals
* Used Data Gateway for service connectivity

---

## 6️⃣ Power BI Service & Dashboard

* Published reports to Power BI Service
* Created Sales Dashboard
* Pinned key visuals:

  * Target Sales
  * Top Selling Customers
  * Orders by Main Category
  * Top Selling Bikes
* Used Q&A feature
* Designed Master Dashboard
* Configured Scheduled Refresh (6 times per day)
* Used Focus Mode editing

---

# 🔹 Business Impact

This BI solution enables AdventureWorks to:

* Monitor revenue and profit performance
* Track sales targets
* Analyze geographical sales trends
* Evaluate product performance
* Perform category-level sales analysis
* Enable controlled data access through RLS
* Support enterprise-grade BI governance
* Empower business users with self-service analytics

---

# 🔹 Technical Skills Demonstrated

✅ Power Query (ETL)
✅ Data Modeling (Star Schema)
✅ DAX Calculations
✅ Advanced Visualizations
✅ RLS Implementation
✅ DirectQuery & Azure SQL
✅ Power BI Service Deployment
✅ Dashboard Design
✅ Scheduled Refresh
✅ Data Governance

---

# 🔹 Tools & Technologies

* Power BI Desktop
* Power BI Service
* SQL Server
* Azure SQL Database
* Excel
* DAX
* Power Query

---

# 🔹 Files Included

* Adventure WorksSales.pbix
* Shaping and Combining Data.pbix
* AdventureWorksLT sales 5.pbix
* Assignment 7.pbix
* Student Survey Dashboard.pbix

---

# ⭐ What Makes This Project Strong?

This is not just a visualization project — it demonstrates:

* Enterprise BI implementation
* Self-service BI enablement
* End-to-end lifecycle management
* Cloud deployment experience
* Real-world reporting architecture

---


