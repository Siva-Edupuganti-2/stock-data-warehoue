# **NSE India Stock Data Warehouse Project 🚀**

Welcome to the **NSE India Stock Data Warehouse Project** repository!  
This project demonstrates a comprehensive **data warehousing solution** using historical stock market data from the **National Stock Exchange of India (1990–2021)**.  
Designed as a portfolio project, it highlights **industry best practices in data engineering, ETL, and data modeling**.

---

## **🏗️ Data Architecture**

The project follows the **Medallion Architecture** (Bronze, Silver, Gold):

### **Bronze Layer**
- Stores raw stock data **as-is** from source CSV files.  
- Data is ingested into **SQL Server** without modifications.  

### **Silver Layer**
- Cleanses, standardizes, and normalizes data for analysis.  
- Handles **missing values, duplicates, and inconsistent formats**.  

### **Gold Layer**
- Contains **business-ready, analytics-ready data** modeled in a **star schema**.  
- Prepares data for downstream analysis in future steps.

---

## **📖 Project Overview**

This project involves:  

- **Data Architecture:** Designing a modern data warehouse using the Medallion Architecture.  
- **ETL Pipelines:** Extracting, transforming, and loading stock data into the warehouse.  
- **Data Modeling:** Developing **fact** and **dimension** tables optimized for analytical queries.

---

## **🎯 Skills Showcased**

This repository demonstrates expertise in:  

- **SQL Development**  
- **Data Engineering & Architecture**  
- **ETL Pipeline Development**  
- **Data Modeling**  
- **Data Cleaning & Transformation**

---

## **🛠️ Tools & Resources**

All tools used are free:  

- **Datasets:** NSE India Stock Data (1990–2021) – CSV files  
- **SQL Server Express:** Lightweight server for hosting your data warehouse  
- **SQL Server Management Studio (SSMS):** GUI for database management  
- **DrawIO:** Design **data flows, ETL pipelines, and star schemas**  
- **Notion:** Project steps, planning, and documentation

---

## **🚀 Project Requirements**

### **Building the Data Warehouse (Data Engineering)**

**Objective:** Consolidate historical stock data into a modern warehouse for analysis.  

**Specifications:**  
- **Data Source:** NSE India Stock Data CSV files  
- **Data Quality:** Cleanse inconsistencies, missing values, and duplicates  
- **Integration:** Create a conformed data model for analytics  
- **Scope:** Historical data from 1990–2021; incremental updates optional  
- **Documentation:** Maintain clear **data model diagrams** and ETL notes

---


