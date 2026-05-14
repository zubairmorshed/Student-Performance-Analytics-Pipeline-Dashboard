# Student Records Analytics Dashboard
A Tableau dashboard analyzing student demographics and academic performance.
This project demonstrates core Analytics Engineering skills, including data cleaning, modeling, visualization, and documentation.

# - Project Overview
This project analyzes a sample student dataset to understand:

Gender distribution, Ethnicity distribution, Math grade distribution, ELA (Reading & Writing) performance, Total student count

The dashboard provides a clear, interactive view of student performance trends and demographic breakdowns.

# - Data Sources
The project uses three CSV files:

student_dim.csv – student demographic information, fact_grades.csv – math grades amd fact_ela.csv – reading and writing scores

All files are included in the raw_data/ folder.

# - Tools Used
Tableau Public – dashboard creation, GitHub – version control and documentation, CSV files – data source and SQL – for data cleaning or modeling steps

# - Dashboard
View the live dashboard on Tableau Public: https://public.tableau.com/app/profile/zubair.morshed/viz/StudentRecordsAnalytics/StudentRecordsAnalytics#1

# - Git Repository Structure
student-records-analytics-engineering-project/
    - documentation (Optional)
    - raw_data/
        - datademographics > student_dim.txt
        - datagrades > fact_grades.txt
        - ela > fact_ela.txt
    - SQL/
        - create_tables > multiple SQL create queries
        - data_cleaning > multiple SQL data cleaning queries
        - exploratory_queries > multiple SQL exploratory queries
        - modeling > fim and fact queries
    - tableau/
        - dashboard > Student Records Analytics.twbx
        - table_extarcts > three clean .csv files contain demographics, grades, and ELA data
    - README.md > This doc
    - README.md > This doc
        - dashboard > Student Records Analytics.twbx
        - table_extarcts > three clean .csv files contain demographics, grades, and ELA data
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
Create relationships using Student Id
Build the dashboard using the worksheets included in this project

📬 Contact
Created by Zubair Morshed  
Aspiring Analytics Engineer
Queens, NY
