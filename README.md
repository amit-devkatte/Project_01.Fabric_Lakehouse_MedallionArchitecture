# Project_01.Fabric_Lakehouse_MedallionArchitecture
End to end Analytical solution for retail mart using Microsoft Fabric platform based on Medallion Architecture.

## 🛍️ **Shopping Mart Analytics – End-to-End Microsoft Fabric Project**

An enterprise-grade analytics solution built using Microsoft Fabric, implementing the Medallion Architecture (Bronze → Silver → Gold) with Lakehouse, Notebooks, Pipelines, Semantic Model, and Power BI Dashboard.

## 📌 Project Overview

This project demonstrates a complete modern data platform implementation using Microsoft Fabric:

🔹 Data Ingestion via Pipelines 🔹 Lakehouse-based Medallion Architecture  🔹 PySpark Transformations (Notebooks)  

🔹 Star Schema Modeling  🔹 Semantic Model (Power BI)  🔹 KPI Dashboard Reporting

The solution simulates a Shopping Mart retail analytics use case, tracking:

Sales Performance   |   Product Performance   |   Customer Insights   |   Category Analysis   |   Monthly Trends

## 🏗️ Architecture Overview
**1️⃣ Medallion Architecture (Fabric Lakehouse)**

### 🔹 Bronze Layer

Raw data ingestion

Structured & unstructured sources

Stored in Lakehouse

### 🔹 Silver Layer

Data cleaning & transformation

Business rule application

Schema refinement

### 🔹 Gold Layer

Business-ready aggregated tables

Optimized for reporting

Star schema implementation

## 🔄 End-to-End Workflow in Fabric

Flow:

Data Ingest → Bronze → Initial Process → Silver → Further Transform → Gold → Data Visualize

## 🧠 Data Modeling (Star Schema)

**Fact Table **     ->    shoppingmart_gold_orders

**Dimension Tables **   ->  DateTable  ,  Reviews,  Social Media,    Web Logs

This design ensures  :  Optimized performance , Clean relationships,  Scalable analytics

## 📓 Transformation Notebooks
### 🔹 Silver Transformation Notebook

**File:**
  NotebookSilverTransformation_ShoppingMartData.ipynb
📎 Local Reference:

**Responsibilities:**
  
  Data cleansing
  
  Null handling
  
  Standardization

  Business logic transformations

### 🔹 Gold Transformation Notebook

**File:**
  NotebookGoldTransformation_ShoppingMart.ipynb
📎 Local Reference: 

ShoppingMart_Analytics_LT_KPI

**Responsibilities:**

  Aggregations
  
  KPI calculations
  
  Business metrics generation
  
  Reporting-ready schema

## 📊 Power BI Dashboard – KPI Report

📄 Full Dashboard PDF:

📌 Key Metrics from Dashboard

From the KPI dashboard:

🔹 Total Sales

🔹 Total Products Sold

🔝 Top 5 Products by Sales

🏆 Top 5 Customers by Sales

📈 Sales by Category

📅 Monthly Sales Trend (2022–2024)


## ⚙️ Technologies Used

Layer	Technology

Data Storage	: **Microsoft Fabric Lakehouse**

Processing  :  	**PySpark Notebooks**

Orchestration  :  	**Fabric Pipelines**

Modeling	:  **Power BI Semantic Model**

Visualization	  :  **Power BI**

Architecture  :  **Medallion (Bronze/Silver/Gold)**

## 🚀 How to Run This Project

Create Microsoft Fabric Workspace

Create Lakehouses (Bronze, Silver, Gold)

Import Notebooks

Run Data Ingestion Pipelines

Execute Silver Notebook

Execute Gold Notebook

Refresh Semantic Model

Open Power BI Report

## 📂 Repository Structure


    ShoppingMartAnalytics/
      │
      ├── notebooks/
      
      │   ├── NotebookSilverTransformation_ShoppingMartData.ipynb
      │   └── NotebookGoldTransformation_ShoppingMart.ipynb
      │
      ├── reports/
      │   └── ShoppingMart_Analytics_LT_KPI.pdf
      │
      ├── images/
      │   ├── Medallion Architecture Design.png
      │   └── Star Model.png
      │
      └── README.md

## 🎯 Business Impact

This project demonstrates:

**Enterprise-grade data architecture

Scalable analytics design

End-to-end Fabric implementation

Real-world retail KPIs

Production-ready modeling standards**

## 👤 Author

Amit Devkatte

Senior Data Analyst | Microsoft Fabric | Power BI | Data Engineering
