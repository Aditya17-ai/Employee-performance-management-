Employee Performance Analytics (SQL + Python)

Analyze employee performance and departmental productivity using SQL (SQLite) for KPI aggregation and Python for analytics and visualization.
This project transforms HR data into actionable business insights, identifying high performers, efficiency trends, and departmental KPIs.


---

Overview

This project demonstrates how to:

Use SQL for feature engineering and KPI calculation

Use Python for data analysis and visualization

Deliver data-driven HR insights in an end-to-end workflow



---

Objectives

Compute department-level performance indicators

Assess employee efficiency and attendance

Visualize relationships between workload, tasks, and ratings

Generate clean and ready-to-use summary reports



---

Project Structure

employee-performance-analytics/  
├── README.md  
├── requirements.txt  
├── data/  
│   └── employees.csv  
├── src/  
│   ├── create_db.py  
│   ├── queries.sql  
│   ├── analyze_performance.py  
│   └── utils.py  
└── outputs/  
    ├── department_kpis.csv  
    ├── performance_summary.csv  
    └── charts/  
        ├── avg_rating_by_department.png  
        ├── performance_vs_hours.png  
        └── task_completion_rate.png


---

Dataset Description

Column	Description

employee_id	Unique employee identifier
name	Employee name
department	Department name (Engineering, Sales, etc.)
role	Role title
date	Record date (YYYY-MM-DD)
tasks_completed	Number of tasks completed
hours_worked	Hours worked on that day
rating	Daily performance rating (1–5)
projects	Active projects
absences	1 if absent, else 0


> The dataset (employees.csv) is synthetic, generated with realistic departmental trends and biases.




---

SQL Logic: src/queries.sql

The SQL script creates views and extracts three analytical datasets:

1. department_kpis – Department-level KPIs:

Average rating

Tasks per department

Total hours

Absence rates



2. employee_summary – Individual performance summaries:

Total tasks, hours, projects, absences

Average ratings

Tasks per hour (efficiency)



3. daily_productivity – Day-wise workload and productivity data.




---

Visualizations

Average Rating by Department

Chart: outputs/charts/avg_rating_by_department.png

<img width="1200" height="750" alt="avg_rating_by_department" src="https://github.com/user-attachments/assets/6b5666ae-d7ed-4a56-948b-2944122a24e0" />  
Mention these Python   
Tableau  
Sql  
Powerapps technologies 
