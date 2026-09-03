# 📊 HR Analytics Dashboard

An interactive Power BI report designed to analyze workforce attrition, demographic trends, and key HR metrics to support data-driven talent retention strategies.

---

## 📝 Project Overview

The HR Analytics Dashboard helps HR leadership and organizational managers identify the root causes of employee turnover. By evaluating key factors such as age, department, job role, salary bands, and work-life balance, this project delivers actionable insights to reduce attrition and improve retention.

---

## 🛠️ Tech Stack

* **Power BI Desktop** – Main platform used for dashboard creation and interactive report layout.
* **Power Query** – Data cleaning, transformation, and custom column creation (e.g., age groups, salary slabs).
* **DAX (Data Analysis Expressions)** – Calculated measures for total employee count, attrition rate, and average tenure.
* **Data Modeling** – Optimized star schema data structure to ensure accurate visual cross-filtering.
* **File Formats** – `.pbix` (Power BI report), `.csv` (Data source), `.md` (Documentation).

---

## 📂 Data Source

* **Dataset**: IBM HR Employee Attrition & Performance dataset.
* **Records**: 1,470 employee records across 38 parameters.
* **Key Fields**: `EmpID`, `Attrition`, `Department`, `JobRole`, `AgeGroup`, `MonthlyIncome`, `OverTime`, `YearsAtCompany`, `WorkLifeBalance`.

---

## 💡 Features & Dashboard Walkthrough

### Business Problem
Employee turnover creates hiring costs, loss of institutional knowledge, and operational disruption. HR teams need visibility into:
1. Which departments and job roles experience the highest turnover rate?
2. How salary bands, age brackets, and overtime impact employee exit rates?
3. What interventions can increase overall retention?

### Goals
* Deliver high-level executive KPIs on workforce stability.
* Highlight specific high-risk employee segments.
* Assist business leaders in designing targeted employee engagement programs.

### Key Metrics & Visual Breakdown
* **Top KPI Cards**: Total Employees (1,470), Attrition Count (238), Attrition Rate (16.19%), Average Age (36.9 yrs), Average Monthly Salary ($6,505), and Average Tenure (7.0 yrs).
* **Attrition by Department**: R&D records the highest total attrition volume (133), followed by Sales (93) and Human Resources (12).
* **Attrition by Job Role**: Identifies high-risk positions like Laboratory Technicians (62 exits), Sales Executives (58 exits), and Research Scientists (47 exits).
* **Attrition by Age Group**: Highlights that early-to-mid career professionals (aged 26–35) form the largest attrition cohort (116 exits).
* **Attrition by Education Field & Salary Slabs**: Cross-examines employee educational background and pay tiers against turnover rates to spot pay-equity or career-growth gaps.

---

## 📈 Business Impact & Recommendations

* **Targeted Retention**: Focus retention programs on entry/mid-level roles (Laboratory Technicians & Sales Executives) where turnover is disproportionately high.
* **Work-Life Balance Alignment**: Review workload and compensation structures for high-overtime job roles.
* **Career Growth Pathways**: Develop clear promotion frameworks for employees in the 26–35 age group to mitigate early-career exit trends.

---

