# 🎓 Student Performance Dashboard – <span style="color:#d5b351">Power BI</span>

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub repo size](https://img.shields.io/github/repo-size/your-username/Student-Performance-Dashboard-PowerBI)]()

An interactive, multi-page Power BI dashboard engineered to analyze student academic performance, attendance patterns, and demographic insights. Built with custom DAX calculations, structured data modeling, and modern UI styling.

---

## 👥 Team Contributions

### 🔹 Student 1: Sanket Jingare – Data Collection & Power Query Cleaning
- Imported 3 Excel sheets (Student, Marks, Attendance)
- Removed duplicates, handled blank/null values
- Standardized text fields and validated data types
- Prepared clean dataset ready for modeling

### 🔹 Student 2: Saloni Khillare – Data Modeling & DAX Measures
- Designed Star Schema relationships
- Created 10+ DAX measures (Total Students, Avg Marks, Pass %, Subject-wise averages)
- Validated measure accuracy and cross-filter behavior

### 🔹 Student 3: Dhananjay Patil – Dashboard Design & Report Publishing
- Designed 3 interactive dashboard pages
- Added KPI cards, charts, slicers, and conditional formatting
- Applied modern Fluent UI theme
- Published to Power BI Service and created GitHub repository

---

## 📋 Summary Table

| Phase | Task | Contributor |
|---|---|---|
| **1** | Data Collection & Power Query Cleaning | Sanket Jingare |
| **2** | Data Modeling & DAX Measures | Saloni Khillare |
| **3** | Dashboard Design & Report Publishing | Dhananjay Patil |

---

## 📊 Dashboard Architecture

### Page 1: Student Overview (Executive Summary)
- **Key Metrics:** Total Students, Average Marks, Pass Rate, Average Attendance, Distinct Departments.
- **Demographics:** Gender distribution (Donut chart), Department-wise student count (Bar chart).
- **Filters:** Interactive slicers for Department, Semester, and Gender.

### Page 2: Performance Analysis
- **Subject-wise Performance:** Column chart comparing Mathematics, Computer Science, and English.
- **Department Comparison:** Bar chart showing average marks by department.
- **Top/Bottom Students:** Table identifying top 10 and bottom 10 performers.
- **Attendance vs Marks:** Scatter plot to analyze correlation.

### Page 3: Attendance Tracking
- **Attendance KPIs:** Overall average, max, min, and count of students below 75%.
- **Departmental Heatmap:** Average attendance by department.
- **Student Details:** Conditional formatting to highlight low attendance (<75%) in red.
- **Semester Trend:** Line chart showing attendance trends across semesters.

---

## 📁 Repository Structure
