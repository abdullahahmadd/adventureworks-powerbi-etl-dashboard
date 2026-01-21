# 🚀 AdventureWorks Power BI ETL Dashboard

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=abdullahahmadd.adventureworks-powerbi-etl-dashboard)

---

## 📑 Table of Contents
- [📌 Overview](#-overview)
- [🎯 Business Task](#-business-task)
- [📂 Dataset Detail](#-dataset-detail)
- [🛠️ Tools & Technologies Used](#️-tools--technologies-used)
- [🧠 Skills Demonstrated](#-skills-demonstrated)
- [🔄 Project Workflow](#-project-workflow)
- [📊 Results](#-results)
- [🔍 Key Findings](#-key-findings)
- [ℹ️ About this Project](#️-about-this-project)

---

## 📌 Overview
This project demonstrates an **end-to-end ETL (Extract, Transform, Load) workflow in Power BI** using Adventure Works sales data.  
The focus is on **data cleaning, transformation, anomaly detection, data modeling, DAX measures, and dashboard creation**, following industry best practices.

---

## 🎯 Business Task
Adventure Works generates a large volume of international sales data stored across multiple yearly files.  
The objective was to:
- Clean and consolidate multi-year sales data
- Identify and remove data anomalies
- Create a reliable data model
- Build a clear and meaningful sales dashboard for decision-making

---

## 📂 Dataset Detail
The project uses **three Excel files**:

- **Order2022.xlsx** – Sales order data for year 2022  
- **Order2023.xlsx** – Sales order data for year 2023  
- **OrderDetails.xlsx** – Line-level sales details (products, quantity, price)

📁 All datasets are available in the `Dataset/` folder.

---

## 🛠️ Tools & Technologies Used
- **Power BI Desktop**
- **Power Query Editor**
- **DAX (Data Analysis Expressions)**
- **Microsoft Excel**
- **GitHub (Version Control & Portfolio Hosting)**

---

## 🧠 Skills Demonstrated
- Data extraction from multiple sources  
- Data cleaning & transformation  
- Data profiling (column quality, distribution, profile)  
- Anomaly detection & removal  
- Appending and merging datasets  
- Data modeling (relationships)  
- DAX measure creation  
- Dashboard design & visualization  

---

## 🔄 Project Workflow
This project follows a structured, end-to-end data workflow:

1. **Data Extraction**
   - Imported multiple Excel files into Power BI using Power Query.

2. **Data Transformation**
   - Removed unnecessary columns.
   - Cleaned empty and invalid rows.
   - Profiled data using column quality, distribution, and statistics.

3. **Anomaly Detection**
   - Identified extreme outliers in UnitPrice.
   - Removed incorrect values to prevent skewed analysis.

4. **Data Integration**
   - Appended Order2022 and Order2023 into a unified Orders table.
   - Merged Orders with OrderDetails using SalesOrderID.

5. **Data Modeling**
   - Created a clean one-to-many relationship between Orders and OrderDetails.

6. **Measures (DAX)**
   - Built core business measures such as Total Sales, Total Quantity, and Average Order Value.

7. **Visualization**
   - Designed a sales dashboard to summarize KPIs and trends.

---

## 📊 Results

### | 1. Sales Order ID Statistics |
|-----------------------|
| ![Sales ID Stats](Results/sales_id_stats.png) |
| Distribution and uniqueness analysis of sales order IDs. |

---

### | 2. Product ID Statistics |
|-----------------------|
| ![Product ID Stats](Results/product_id_stats.png) |
| Product-level distribution used to validate data consistency. |

---

### | 3. Order Quantity Statistics |
|-----------------------|
| ![Order Quantity Stats](Results/order_qty_stats.png) |
| Analysis of quantities sold to identify unusual patterns. |

---

### | 4. Unit Price Statistics |
|-----------------------|
| ![Unit Price Stats](Results/unit_price_stats.png) |
| Price profiling used to detect and remove outliers. |

---

### | 5. Data Model |
|-----------------------|
| ![Data Modeling](Results/data_modeling.png) |
| Clean one-to-many relationship between Orders and Order Details. |

---

### | 6. Final Sales Dashboard |
|-----------------------|
| ![Sales Dashboard](Results/adventureworks_sales_dashboard.png) |
| Final Power BI dashboard summarizing sales performance. |

---

## 🔍 Key Findings
- Outlier prices significantly impacted average sales metrics and were successfully removed.
- Clean data modeling ensured accurate aggregation and analysis.
- Consolidating multi-year data improved trend visibility.
- The final dashboard provides a clear overview of sales performance.

---

## ℹ️ About this Project
This project was completed as part of the **Microsoft Power BI Data Analyst Professional Certificate**, specifically the **Extract, Transform, and Load Data in Power BI** course.  
It is designed to showcase **practical ETL, modeling, and reporting skills** in a real-world business scenario.

---

⭐ If you find this project useful, feel free to star the repository!
