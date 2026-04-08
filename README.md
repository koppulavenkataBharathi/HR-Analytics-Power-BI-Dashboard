# HR Data Analytics Dashboard (Power BI Project)

## Project Overview

The **HR Data Analytics Dashboard** is a Power BI project developed to analyze employee workforce data and identify key factors influencing employee attrition.

This dashboard helps HR teams understand workforce trends, employee demographics, and attrition patterns to support **data-driven decision making**.

By transforming raw HR data into meaningful visual insights, the project highlights important workforce metrics and provides recommendations to improve employee retention.

---

## Business Problem

Organizations often struggle to understand the reasons behind employee attrition and workforce behavior. High attrition leads to increased recruitment costs, productivity loss, and organizational disruption.

This project aims to analyze HR data to identify:

* Employee attrition patterns
* Department-wise employee distribution
* Workforce demographics
* Key factors influencing employee turnover

---

## Tools & Technologies Used

* **Power BI** – Data Visualization
* **Power Query** – Data Cleaning and Transformation
* **DAX (Data Analysis Expressions)** – Data Calculations
* **Kaggle Dataset** – HR Employee Data
* **Microsoft Excel** – Data Preparation

---

## Dataset Information

The dataset contains employee information including:

* Employee ID
* Age
* Gender
* Department
* Job Role
* Monthly Salary
* Education Field
* Marital Status
* Years at Company
* Years Since Last Promotion
* Job Satisfaction
* Overtime
* Attrition Status

These attributes help analyze workforce behavior and identify attrition trends.

Dataset Source:
https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction

---

## Data Cleaning & Preparation

Data cleaning was performed using **Power Query Editor** to ensure data quality.

Steps performed:

* Removed duplicate records
* Handled missing values
* Converted column data types
* Renamed columns for better readability
* Created calculated columns
* Removed unnecessary fields

This ensured the dataset was structured and ready for analysis.

---

## Data Modeling

A structured data model was created using **Fact and Dimension tables**.

### Fact Table

**Fact Employee**

* Contains measurable employee metrics such as salary, experience, and attrition status.

### Dimension Tables

**Dim Employee**

* Employee demographic information such as age, gender, education, and marital status.

**Dim Department**

* Department related information.

Relationships were created using **Employee Number** to build an efficient data model.

---

## DAX Measures

Several DAX measures were created for analysis:

Total Employees

Attrition Count

Attrition Rate

Average Salary

Average Age

Average Years at Company

These measures helped calculate important HR metrics used in the dashboard.

---

## Dashboard Pages

The Power BI dashboard contains **three analytical pages**.

### 1. HR Overview Dashboard

This page provides a summary of workforce metrics and attrition insights.

Key Visualizations:

* KPI Cards (Total Employees, Attrition Count, Attrition Rate)
* Attrition by Department
* Attrition by Job Role
* Attrition by Gender
* Attrition by Promotion Gap
* Promotion Gap vs Years at Company

These visuals help HR quickly understand workforce trends.

---

### 2. Employee Demographics Dashboard

This dashboard focuses on employee characteristics.

Visualizations include:

* Attrition by Age Group
* Attrition by Marital Status
* Attrition by Education Field
* Attrition by Experience Level
* Attrition by Overtime

This analysis helps HR understand how demographic factors influence attrition.

---

### 3. Attrition Factors Dashboard

This page identifies major factors that contribute to employee attrition.

Key visualizations:

* Attrition by Salary Group
* Attrition by Experience Level
* Attrition by Job Satisfaction
* Attrition by Salary Hike
* Attrition by Promotion Gap
* Attrition by Department and Job Role

This helps HR identify critical areas that require improvement.

---

## Key Insights

1. **Early career employees have higher attrition**

   * Employees with 0–5 years of experience leave more frequently.

2. **Lower salary groups experience higher attrition**

   * Employees with lower salary levels are more likely to leave.

3. **Sales and R&D departments show higher attrition**

   * These departments have the highest turnover rates.

4. **Younger employees change jobs more frequently**

   * Employees under 30 show higher attrition compared to older employees.

5. **Overtime work increases attrition**

   * Employees working overtime have higher chances of leaving.

6. **Low job satisfaction strongly impacts attrition**

   * Employees with lower job satisfaction show higher turnover.

---

## Recommendations

Based on the analysis, the following actions can help reduce employee attrition:

* Improve employee retention programs for early-career employees
* Provide competitive salary structures
* Reduce excessive overtime to improve work-life balance
* Offer clear promotion and career growth opportunities
* Increase employee engagement and job satisfaction

---

## Conclusion

The **HR Data Analytics Dashboard** demonstrates how data visualization can provide meaningful insights into workforce trends and employee attrition.

Using Power BI, HR data was transformed into interactive dashboards that help organizations make **data-driven HR decisions**.

This project highlights the importance of analytics in improving employee retention strategies and workforce planning.

---

## Author

**Venkata Bharathi Koppula**

Aspiring Data Analyst

Skills:

* Power BI
* Data Analytics
* SQL
* Excel
* Data Visualization
