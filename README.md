## Student Performance Analytics Pipeline & Dashboard

An end-to-end analytics project simulating an Analytics Engineer workflow, including data preparation, transformation, validation, and reporting using SQL and Tableau.

---

## Project Overview

This project analyzes student demographics and academic performance by transforming raw datasets into structured, analysis-ready data models and visual dashboards.

It demonstrates how raw data can be converted into reliable reporting outputs through data cleaning, transformation, and validation.

---

## Data Architecture

The project follows a simplified analytics workflow:

Raw Data (CSV)  
→ Data Cleaning & Transformation (SQL)  
→ Structured Reporting Layer  
→ Tableau Dashboard  

---

## Data Modeling Approach

The dataset is organized using a fact/dimension-style approach:

- **student_dim.csv** → Dimension table (student demographics)
- **fact_grades.csv** → Fact table (math scores)
- **fact_ela.csv** → Fact table (reading & writing performance)

Relationships are created using `student_id` to support analytical queries and reporting.

---

## Data Transformation & Validation

SQL is used to:

- Clean and standardize raw data  
- Validate consistency across datasets  
- Handle missing or null values  
- Ensure alignment of metrics between datasets  
- Prepare aggregated outputs for reporting  

---

## Tools Used

- **SQL** – Data cleaning, transformation, and validation  
- **Tableau Public** – Dashboard development and visualization  
- **GitHub** – Version control and documentation  

---

## Dashboard

[View the Tableau Dashboard](https://public.tableau.com/app/profile/zubair.morshed/viz/StudentPerformanceAnalyticsDashboard_17787789622650/StudentPerformanceAnalyticsDashboard)

The dashboard presents:

- Student performance trends  
- Demographic breakdowns  
- Comparative analysis across subjects  

---

## What This Project Demonstrates

- Structuring raw data into analysis-ready datasets  
- Applying data transformation and validation techniques  
- Designing data models to support reporting  
- Building dashboards based on validated data outputs  
- Linking backend data preparation to front-end analytics  

---

## Repository Structure

``

# - Key Insights
Total students: 20
Gender split: 11 Male, 9 Female
Ethnicity distribution: White (30%), Asian (20%), Black (20%), Hispanic (20%), Null (10%)
Math grades range from 73–95
ELA scores show variation between reading and writing performance

# - How to Reproduce
Download the CSV files from the raw_data/ folder
Open Tableau Public (Link provided above)
Upload all three CSVs
Create relationships using student_id
Build the dashboard using the worksheets included in this project

# - Contact
Created by Zubair Morshed  
Aspiring Analytics Engineer
Queens, NY
