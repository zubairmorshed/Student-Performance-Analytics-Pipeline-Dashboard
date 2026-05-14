# Student Performance Analytics Pipeline & Dashboard

An end-to-end analytics project demonstrating how raw data is transformed into structured, analysis-ready datasets and interactive dashboards using SQL and Tableau.

This project reflects core Analytics Engineering concepts, including data cleaning, transformation, validation, dimensional modeling, and reporting.

---

## Project Overview

This project analyzes student demographics and academic performance by transforming raw datasets into a structured reporting layer that supports analytical queries and dashboard visualization.

The focus is on building reliable datasets through data quality validation and transformation logic, ensuring accurate and consistent reporting outputs.

---

## End-to-End Workflow

Raw Data (CSV)  
→ Data Cleaning & Transformation (SQL)  
→ Exploratory Validation  
→ Dimensional Modeling (Fact & Dimension Tables)  
→ Reporting Layer (Tableau Extracts)  
→ Dashboard Visualization (Tableau)

---

## Data Architecture

The data pipeline is designed using a structured, layered approach:

- Raw Layer  
  Source CSV files organized by domain (demographics, grades, ELA)

- Transformation Layer (SQL)  
  Data cleaning, aggregation, and validation logic

- Modeling Layer  
  Fact and dimension tables for analytics

- Reporting Layer  
  Clean datasets prepared for Tableau

- Visualization Layer  
  Interactive dashboards in Tableau

---

## Repository Structure

This structure separates raw data, transformation logic, validation, and reporting layers to simulate a real-world analytics engineering pipeline.

student-performance-analytics/
|-- raw_data/
|   |-- data_demographics/
|   |-- data_grades/
|   |-- data_ela/
|
|-- sql/
|   |-- create_tables/
|   |-- data_cleaning/
|   |-- exploratory_queries/
|   |-- modeling/
|
|-- tableau/
|   |-- dashboard/
|   |-- table_extracts/
|
|-- documentation/
|
|-- dashboard_peek.png
|-- README.md

---

## Data Modeling Approach

- Dimension Table: student_dim  
- Fact Tables: fact_grades, fact_ela  

All tables are linked using student_id.

---

## Data Transformation & Validation

- Data cleaning and standardization
- Handling missing values
- Validating consistency across datasets
- Preparing data for reporting

---

## Dashboard

[View the Tableau Dashboard](https://public.tableau.com/app/profile/zubair.morshed/viz/StudentPerformanceAnalyticsDashboard_17787789622650/StudentPerformanceAnalyticsDashboard)

---

## What This Project Demonstrates

- End-to-end analytics workflow
- SQL-based transformation and validation
- Data modeling (fact and dimension tables)
- Data quality and reporting readiness

---

## How to Reproduce

1. Download data from raw_data
2. Review SQL scripts
3. Load data into Tableau
4. Create relationships using student_id

---

## Author

Zubair Morshed
Queens, NY

QA Engineer transitioning into Analytics Engineering
