# Customer_behavior_analysis
# Data Analytics Project

## Overview

This project demonstrates an end-to-end **data analytics workflow**, covering data ingestion, exploratory data analysis (EDA), data cleaning, SQL-based analysis, and business intelligence reporting. The goal is to extract actionable insights from raw data and present them through an interactive **Power BI dashboard**, a detailed **analysis report**, and a **presentation deck**.

This project is designed to showcase practical skills expected from a **Data Analyst**, including Python, SQL, and data visualization.

---

## Dataset

* Source: Public
* Size: Medium-scale structured dataset
* Description: Contains transactional and business-related records used to analyze trends, performance, and key metrics

> The dataset is loaded and processed using Python before being stored and queried using SQL databases.

---

## Tools & Technologies

* **Programming & Analysis**: Python (Pandas)
* **Databases**: MySQL
* **SQL**: Joins, Subqueries, Aggregations, Window Functions
* **Visualization**: Power BI
* **IDE**: VS Code / Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

* Imported raw CSV data using Python
* Checked schema, data types, and basic structure

### 2. Exploratory Data Analysis (EDA)

* Analyzed data distribution and trends
* Identified missing values and outliers
* Generated summary statistics and visualizations

### 3. Data Cleaning & Preparation

* Handled missing and duplicate values
* Standardized column names and formats
* Converted data types for analysis and SQL compatibility

### 4. SQL Analysis

* Loaded cleaned data into MySQL
* Wrote optimized SQL queries to answer business questions
* Used:
  * GROUP BY & HAVING
  * JOINs
  * Subqueries
  * Window functions

### 5. Power BI Dashboard

* Connected Power BI to SQL database
* Built interactive dashboards with:
  * KPIs
  * Filters & slicers
  * Trend and comparison charts

## Dashboard

The Power BI dashboard provides:

* High-level KPIs
* Time-based trend analysis
* Category and performance comparisons
* Interactive filtering for deeper insights

> Designed with a recruiter and business-user-friendly approach.

---

## Key Results & Insights

* Identified major trends and patterns in the data
* Highlighted top-performing and underperforming segments
* Provided data-driven recommendations for business decisions

---

## How to Run This Project

1. **Open Customer_Analysis.ipynb notebook**
   
   This file contains:
   
    * Data Import
    * Data exploration
    * Data cleaning
    * Connection to SQL Database

3. **Load the data from Python notebook into MySQL **

   * Create the database in MySQL
   * Run Python code to load data into SQL database
   * Open customer_behavior_sql_queries.sql
   * Answer Business Questions using SQL Queries

4. **Connect the SQL Database to Power BI**

   * Connect Power BI to the database
   * Refresh data to view insights
   * Open customer_behavior_dashboard.pbix
   * Create interactive dashboard in Power BI

---

## Project Highlights

* End-to-end data analytics pipeline
* Strong focus on SQL and business insights
* Recruiter-friendly documentation and visuals
* Real-world analytics workflow

