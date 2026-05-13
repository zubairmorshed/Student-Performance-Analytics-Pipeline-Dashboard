# \# Student Records Analytics Engineering Project

# \- This project demonstrates an end-to-end Analytics Engineering workflow using the following:

# \- Raw K-12 student data (Demographics, Grades, ELA) files with realistic data quality issues

# \- SQL Server Express for data cleaning and modeling with table creation, cleaning, and modeling

# \- Tableau Public for interactive dashboards using the above-mentioned tables 

# \- GitHub for version control and documentation

# \- Project Structure
Code
documentation/          ← optional notes, data dictionary, ERD (future use)
raw_data/               ← original TXT files

SQL/
  create_tables/        ← table creation scripts
  data_cleaning/        ← cleaning + deduplication scripts
  modeling/             ← student_dim, fact_grades, fact_ela
  exploratory_queries/  ← analysis queries

tableau/                ← dashboard files (coming soon)

README.md

# \- Data Pipeline

Raw Data - Demographics. Grades, ELA scores

Table Creation - Created base tables for raw, clean, and modeling layers

Cleaning Layer = Standardized column names, Fixed data types, Removed duplicates, Created “dupliclean” tables

Modeling Layer = student_dim. fact_grades, fact_ela

Exploratory Queries = Student counts, Grade allocation. ELA trends, Demographic allocations, Course averages, 

Tableau Dashboard (Coming Soon) - Will visualize student performance and trends

# \- Key SQL Files
Table Creation > create_demographics_tables.sql, create_grades_tables.sql, create_ela_tables.sql

Cleaning > dupliclean_demographics.sql, dupliclean_grades.sql, dupliclean_ela.sql

Modeling > student_dim.sql, fact_grades.sql, fact_ela.sql

Exploratory Queries > Examples: grade_allocation_by_course.sql, ela_scores_by_term.sql, gender_allocation.sql, course_avg.sql

▶️ How to Reproduce
Create a SQL Server database named StudentRecords > Execute the scripts in SQL/create_tables/ > Execute the cleaning scripts in SQL/data_cleaning/ > Execute the modeling scripts in SQL/modeling/ > Execute the exploratory queries in SQL/exploratory_queries/

Connect Tableau to the database for visualization

📊 Tableau Dashboard
Coming soon  
A link will be added here once the dashboard is published.

