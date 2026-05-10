# HR Analytics Dashboard

This project presents a comprehensive **HR analytics solution** built using Tableau to help HR managers and business stakeholders analyze workforce data through interactive dashboards and employee-level reporting.

The dashboard provides insights into:
- Workforce overview and employee trends
- Employee demographics and distribution
- Salary and income analysis
- Detailed employee records for operational analysis

The project is designed as a portfolio project showcasing:
- Interactive Tableau dashboard development
- HR data visualization
- KPI reporting and workforce analytics
- Dashboard design and user-driven filtering

---

## Dashboard Overview

The HR dashboard is divided into four major sections:

1. **Overview**
2. **Demographics**
3. **Income Analysis**
4. **Employee Records**

The dashboard enables users to interactively filter and analyze employee information across multiple dimensions.

---

## Project Objectives

### Overview Analysis

Provide high-level workforce insights including:
- Total hired employees
- Active employees
- Terminated employees
- Employee hiring and termination trends over time
- Employee distribution across departments and job titles
- HQ vs branch employee comparison
- Geographic employee distribution

### Demographics Analysis

Analyze workforce composition through:
- Gender distribution
- Age group distribution
- Education level analysis
- Employee count by age and education
- Correlation between education background and performance ratings

### Income Analysis

Analyze salary-related patterns including:
- Salary comparison across education levels
- Gender-based salary comparison
- Relationship between age and salary by department

### Employee Records

Provide detailed employee-level reporting including:
- Employee name
- Department
- Position
- Gender
- Age
- Education
- Salary

Users can dynamically filter employee records using dashboard filters.

---

## Dashboard Features

### KPI Cards (BANs)
- Total Hired Employees
- Active Employees
- Terminated Employees

### Charts & Visualizations
- Line + Area Charts
- Bar Charts
- Donut Charts
- Heatmaps
- Map Visualizations
- Barbell Charts
- Scatter Plots
- Employee Record Views

### Interactivity
- Dynamic dashboard filters
- Cross-filtering between visuals
- Interactive employee analysis

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Tableau Public | Dashboard Development |
| Python | HR Dataset Generation |
| CSV Files | Data Source |
| Git & GitHub | Version Control |

---

## Dashboard Screenshots

### Overview Dashboard
![Overview Dashboard](images/dashboard_overview.png)

### Demographics Dashboard
![Demographics Dashboard](images/demographics_view.png)

### Income Analysis Dashboard
![Income Analysis](images/income_analysis.png)

### Employee Records Dashboard
![Employee Records](images/employee_records.png)

---

## Repository Structure

```text
hr-analytics-dashboard/
│
├── data-generation/
│   └── generate_hr_data.py
│
├── datasets/
│   └── hr_data.csv
│
├── images/
│   ├── dashboard_overview.png
│   ├── demographics_view.png
│   ├── income_analysis.png
│   └── employee_records.png
│
├── hr-dashboard.twbx
│
├── README.md
├── LICENSE
├── .gitignore
└── requirements.txt
```

---

## [Tableau Public Dashboard](https://public.tableau.com/app/profile/chiraggh/viz/HRDashboard_17784344141840/SummaryDashboard)

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

---