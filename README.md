# 🍔 Online Food Delivery Data Warehouse & BI System

🚀 End-to-End Data Warehousing & Business Intelligence Project  
Built using **SQL Server, SSIS, SSAS, Excel, and Power BI**

---

## 📌 Project Overview

This project demonstrates the complete implementation of a **Data Warehouse and Business Intelligence solution** using an Online Food Ordering dataset.

The system transforms raw transactional data into meaningful insights through:
- ETL pipelines
- Dimensional modelling
- OLAP cube analysis
- Interactive dashboards

---

## 🏗️ Architecture

### 🔹 Layers
- **Data Sources** → OLTP database + CSV/TXT files  
- **ETL Layer (SSIS)** → Extraction, Transformation, Loading  
- **Data Warehouse** → Star Schema  
- **BI Layer** → SSAS, Excel, Power BI  

---

## ⭐ Key Features

### 📊 Data Warehouse Design
- Star Schema implementation
- Fact Table: `Fact_Order`
- Dimension Tables:
  - `Dim_Date`
  - `Dim_Customer (SCD Type 2)`
  - `Dim_Restaurant (SCD Type 1)`

---

### 🔄 ETL Process (SSIS)
- Multi-source data integration (DB + CSV)
- Data cleansing & transformation
- Lookup transformations
- Derived columns
- Surrogate key generation

---

### ⏳ Advanced Concept
**Accumulating Fact Table Implementation**
- Tracks order lifecycle
- Measures processing time:
  - Order creation time
  - Order completion time
  - Processing duration

---

### 🧠 OLAP Cube (SSAS)
- Built multidimensional cube
- Measures:
  - Total Amount
  - Delivery Fee
- Hierarchies:
  - Date (Year → Month)
  - Restaurant (City → Name)

---

### 📈 OLAP Operations
- Roll-up
- Drill-down
- Slice
- Dice
- Pivot

---

### 📊 Power BI Dashboard
- KPI Cards (Total Sales, Delivery Fee)
- Bar Charts (Sales by City)
- Pie Charts (Distribution)
- Matrix Visual
- Slicers for interactivity

---

## 🛠️ Tech Stack

- Microsoft SQL Server
- SSIS (ETL)
- SSAS (Cube)
- Power BI
- Excel (Pivot Tables)

---


## 💡 Key Learnings

- End-to-end DW/BI pipeline design
- ETL development with SSIS
- Slowly Changing Dimensions (SCD)
- OLAP cube design & analysis
- Data visualization with Power BI

---

## 🔗 Dataset Source

Kaggle - Food Delivery Order History Dataset  
https://www.kaggle.com/datasets/sujalsuthar/food-delivery-order-history-data

## 👩‍💻 Author

**Pabodha P.G**  
IT23680234  
BSc (Hons) in IT – Data Science  

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
