# HR-Analytics-Dashboard

An interactive Power BI dashboard analyzing employee attrition across 1,470 employees. It explores attrition by department, age, gender, education, salary, job role, and tenure using DAX, Power Query, and slicers to turn HR data into clear, actionable insights.

## 📌 Project Overview

Employee attrition is an important HR metric because frequent turnover can affect workforce stability, recruitment costs, productivity, and organizational planning.

This project provides an overview of the workforce and lets users explore attrition patterns across multiple employee attributes.

The dashboard includes department-level filtering for:

- Human Resources
- Research & Development
- Sales

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Attrition | 237 |
| Attrition Rate | 16.1% |
| Average Age | 37 |
| Average Salary | 6.5K |
| Average Years at Company | 7.0 |

## 📈 Dashboard Visuals

- Attrition by Gender (Treemap)
- Attrition by Education Field (Donut Chart)
- Attrition by Age Group (Column Chart)
- Attrition by Job Role and Job Level (Matrix)
- Attrition by Salary Slab (Horizontal Bar Chart)
- Attrition by Years at Company (Area Chart)
- Attrition by Job Role (Horizontal Bar Chart)

## 🔍 Key Insights

- The overall attrition rate is **16.1%**, with 237 of 1,470 employees leaving.
- The **26–35 age group** has the highest attrition (116 employees).
- **150 male** and **87 female** employees left the company.
- **Life Sciences (38%)** and **Medical (27%)** backgrounds lead attrition.
- Employees earning **up to 5K** account for 163 departures.
- Attrition peaks around **year 1–2** of tenure (59 employees).
- **Laboratory Technician (62)** and **Sales Executive (57)** are the most affected roles.

## 🛠️ Tools Used

- **Power BI Desktop** for visualizations and report design
- **Power Query** for data extraction, transformation, and loading
- **DAX** for custom measures and calculations
- **Slicers and page filters** for interactive filtering

## 🗂️ Dataset

The project uses an HR attrition dataset with 1,470 employee records across multiple departments. Key columns include:

- Department
- Attrition Status
- Age and Age Group
- Gender
- Education Field
- Job Role and Job Level
- Monthly Income and Salary Slab
- Years at Company and Total Working Years
