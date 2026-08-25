# HR_Attrition_Workforce_Analytics
It consists of data source file (.csv), tableau packaged workbook (.twbx), insight file (.docx), images of worksheets (.png) and a readme.md file

## Professional Summary

This project presents an end-to-end analysis of employee attrition using Tableau. It examines compensation structure, workforce demographics, and the factors most associated with employee turnover, translating raw HR data into a set of interactive visualizations and actionable business insights. The objective is to demonstrate the ability to convert operational data into decision-ready analytics for HR and business stakeholders.

## Skills & Tools

- **Data Visualization:** Tableau (Packaged Workbook)
- **Data Analysis:** Exploratory Data Analysis (EDA), descriptive statistics, correlation analysis
- **Data Handling:** CSV data cleaning and preparation
- **Core Competencies:** Dashboard design, business insight development, workforce analytics

## Project Overview

The dashboard is built on an employee-level HR dataset covering 1,470 records and 35 attributes, including compensation, department, job role, tenure, and attrition status. Six visualizations were developed to explore this data from complementary angles:

| Visualization | Purpose |
|---|---|
| Bar Chart | Average monthly income by job role |
| Box Plot | Income distribution and spread by education field |
| Histogram | Age distribution segmented by attrition status |
| Pie Chart | Departmental headcount composition |
| Scatter Plot | Relationship between tenure, income, and job level |
| Stacked Bar Chart | Attrition rate by overtime status |

Together, these visuals support analysis of compensation equity, workforce risk factors, and departmental composition.

## Repository Structure

```
├── Tarmin_Tableau_Project.twbx         # Packaged Tableau workbook (dashboard + data source)
├── Human_Resources.csv                 # Source dataset (1,470 employee records)
├── Worksheets/                         # Images of individual worksheets
│   ├── bar_chart.png
│   ├── box_plot.png
│   ├── histogram.png
│   ├── pie_chart.png
│   ├── scatter_plot.png
|   ├── Dashboard.png
│   └── stacked_bar_chart.png
├── HR Attrition Insights.docx          # Business insights
└── README.md                           # Project documentation
```

## Data Analysis Process

1. **Data Preparation:** The HR dataset was reviewed for structure, data types, and completeness prior to import into Tableau.
2. **Exploratory Data Analysis:** Key variables — income, job role, department, tenure, age, and attrition — were profiled to identify initial patterns and relationships.
3. **Dashboard Design:** Six worksheets were developed in Tableau, each targeting a specific business question (compensation by role, pay equity by education, attrition by age, departmental composition, tenure vs. income, and overtime's effect on attrition).
4. **Insight Development:** Patterns identified in the visualizations were quantified using summary statistics and correlation analysis, then translated into concise, business-relevant findings (see `HR Attrition Insights.docx`).
5. **Validation:** Figures cited in the insights document were cross-checked against the source dataset to ensure accuracy.

## Business Impact

- **Retention risk identification:** Overtime status and employee age were identified as the strongest indicators of attrition risk, providing HR with concrete criteria for targeted retention programs.
- **Compensation review support:** The analysis surfaces significant pay differences by job level and education field, offering a data-backed starting point for compensation equity reviews.
- **Workforce planning:** Departmental headcount and tenure patterns highlight where attrition trends are concentrated, helping leadership prioritize where retention efforts will have the greatest effect.
- **Decision-ready reporting:** The interactive Tableau dashboard allows stakeholders to explore the underlying data directly, reducing reliance on static reports for ongoing HR decision-making.

## 👤 Author

**Tarmin**  
Aspiring Data Analyst with hands-on experience in Excel, SQL, Python, PowerBI, Tableau and AI/ML. This repository showcases real-world projects built to solve practical data problems.
