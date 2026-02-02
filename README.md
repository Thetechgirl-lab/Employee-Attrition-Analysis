# Employee-Attrition-Analysis
Employee Attrition Analysis (Power BI Project)
Project Overview

This project explores employee attrition using HR data to uncover trends, risk factors, and retention insights. An interactive Power BI dashboard was built to help HR teams understand where attrition occurs and why.

 Objectives

Measure total workforce size and attrition rate

Identify high-attrition departments and job roles

Analyze demographic, job-related, and engagement factors

Support HR decision-making with visual insights

 Dataset

One row per employee

Key fields:

EmployeeNumber (unique ID)

EmployeeCount (1 per employee)

Attrition (Yes/No)

Department, JobRole, Gender, Age

MonthlyIncome, YearsAtCompany, OverTime

JobSatisfaction, WorkLifeBalance
Data Preparation

Verified data types and cleaned fields

Created DAX measures for KPIs

Calculated attrition rate, average age, salary, and tenure

Created age groups and tenure groups

Used SUM(EmployeeCount) for accurate employee counts

Dashboard Features

KPI cards: Total Employees, Attrition, Attrition Rate, Avg Age, Avg Salary, Avg Tenure

Attrition analysis by department, job role, and gender

Overtime, income, and satisfaction vs attrition analysis

Interactive slicers for filtering

🔍 Key Insights

Attrition is concentrated in specific departments and roles

Employees working overtime show higher attrition

Lower job satisfaction and work-life balance are linked to higher turnover

Employees with shorter tenure are more likely to leave

 Tools Used

Power BI (Data modeling, DAX, visualization)

Python (Pandas) for validation

Excel / CSV files
