Employee Performance Analytics System
Tech Stack
Python — Data analysis, automation, visualization
SQLite / SQL — KPI aggregation and querying
Tableau — Interactive dashboards and analytics reporting
Microsoft Power Apps — HR management interface and workflow automation
Employee Performance Analytics (SQL + Python + Tableau + PowerApps)
Analyze employee performance and departmental productivity using SQL (SQLite) for KPI aggregation, Python for analytics and visualization, Tableau for interactive dashboards, and PowerApps for HR workflow integration.
This project transforms HR data into actionable business insights, identifying high performers, productivity trends, attendance patterns, and departmental KPIs.
Overview
This project demonstrates how to:
Use SQL for feature engineering and KPI calculation
Use Python for data cleaning, analysis, and visualization
Build Tableau dashboards for business reporting
Integrate insights into PowerApps for HR operations
Deliver an end-to-end data analytics workflow
Objectives
Compute department-level performance indicators
Analyze employee efficiency and attendance
Visualize relationships between workload, tasks, and ratings
Track departmental productivity trends
Create interactive dashboards for HR managers
Generate automated summary reports
Project Structure
Bash
employee-performance-analytics/
├── README.md
├── requirements.txt
├── data/
│   └── employees.csv
├── src/
│   ├── create_db.py
│   ├── queries.sql
│   ├── analyze_performance.py
│   ├── tableau_export.py
│   └── utils.py
├── tableau/
│   └── employee_dashboard.twb
├── powerapps/
│   └── integration_notes.md
└── outputs/
    ├── department_kpis.csv
    ├── performance_summary.csv
    ├── dashboard_data.csv
    └── charts/
        ├── avg_rating_by_department.png
        ├── performance_vs_hours.png
        ├── task_completion_rate.png
        └── attendance_trends.png
Dataset Description
Column
Description
employee_id
Unique employee identifier
name
Employee name
department
Department name
role
Employee role
date
Record date
tasks_completed
Tasks completed per day
hours_worked
Total working hours
rating
Performance rating (1–5)
projects
Active projects count
absences
1 if absent, else 0
The dataset is synthetic and generated with realistic departmental productivity patterns.
SQL Analytics (queries.sql)
The SQL workflow generates:
1. department_kpis
Department-level insights:
Average employee ratings
Total completed tasks
Productivity scores
Absence percentages
Total working hours
2. employee_summary
Employee-level metrics:
Total tasks completed
Average ratings
Project counts
Attendance records
Tasks-per-hour efficiency
3. daily_productivity
Daily operational analytics:
Workload distribution
Productivity fluctuations
Performance trends over time
Python Analytics
Using Python libraries:
pandas → Data manipulation
matplotlib & seaborn → Visualizations
sqlite3 → Database interaction
numpy → Statistical analysis
Key Analyses
Employee efficiency ranking
Correlation between hours worked and ratings
Department productivity comparison
Attendance impact analysis
Tableau Dashboard Features
Built in Tableau:
Department KPI dashboard
Employee performance leaderboard
Attendance heatmaps
Productivity trend charts
Interactive filters by department and role
Dashboard Insights
Top-performing departments
Employees with highest efficiency
Attendance vs productivity patterns
Monthly workload distribution
PowerApps Integration
Integrated with Microsoft Power Apps to:
Create HR management forms
Display real-time employee KPIs
Automate performance review workflows
Enable manager-level approvals
Track attendance and productivity centrally
Visualizations
Average Rating by Department
Compare departmental performance quality
Performance vs Hours Worked
Identify productivity saturation trends
Task Completion Rate
Analyze operational efficiency
Attendance Trends
Detect absenteeism impact on productivity
Business Impact
This project helps organizations:
Improve workforce productivity
Identify high-performing employees
Detect operational inefficiencies
Support data-driven HR decisions
Automate reporting workflows
Enhance employee performance tracking
Skills Demonstrated
SQL Query Optimization
Data Engineering
Exploratory Data Analysis (EDA)
KPI Development
Dashboard Design
HR Analytics
Business Intelligence
Workflow Automation
Data Visualization
Future Enhancements
Machine Learning-based performance prediction
Employee attrition forecasting
Real-time dashboard deployment
Cloud database integration
API integration with HRMS platforms
Automated email reporting system
