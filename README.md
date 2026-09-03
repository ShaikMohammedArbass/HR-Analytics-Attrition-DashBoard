# 📊 HR Analytics: Workforce & Attrition Intelligence Dashboard

An interactive Power BI dashboard designed to analyze workforce demographics, evaluate employee attrition dynamics, and uncover strategic retention insights across organizational departments.

---

## Short Description / Purpose

The HR Analytics Dashboard provides an end-to-end evaluation of corporate workforce data to track employee turnover, salary distributions, and performance metrics. Built using Power BI, DAX, and Power Query, this tool converts raw HR records into actionable visual reports, allowing HR business partners and talent leaders to identify high-risk turnover factors, optimize compensation structures, and improve employee retention strategies.

---

## Tech Stack

The dashboard was built using the following tools and analytics practices:

* 📊 **Power BI Desktop** – Core data visualization platform used for dashboard layout and interactive visual design.
* 📂 **Power Query** – Applied data transformation, column profiling, and attribute type enforcement.
* 🧠 **DAX (Data Analysis Expressions)** – Programmed measures and calculated columns for key KPIs like Attrition Rate, Average Monthly Income, and Age Group segmentations.
* 📐 **Data Modeling** – Established analytical relationships and attribute hierarchies across employee attributes, salary slabs, and departmental structures.
* 📁 **File Format** – `.pbix` for interactive development and `.csv` for source transaction records.

---

## Data Source

The project analyzes a comprehensive HR dataset covering employee attributes, satisfaction scores, compensation metrics, and tenure history:

* **Source**: Corporate HR Analytics Records (1,480 total employee profiles).
* **Key Fields**: `EmpID`, `Age`, `AgeGroup`, `Attrition`, `Department`, `JobRole`, `MonthlyIncome`, `SalarySlab`, `JobSatisfaction`, `EnvironmentSatisfaction`, `YearsAtCompany`, `YearsSinceLastPromotion`.

---

## Features / Highlights

### Business Problem
Human Resources leadership often struggles to isolate the root causes of employee turnover and identify which departments or compensation tiers experience the highest attrition risks. Key operational questions include:
* What is the organization's overall attrition rate, and which age groups or salary slabs suffer the highest turnover?
* How do job satisfaction, environment satisfaction, and overtime work impact employee retention?
* Are employee promotion cycles and manager tenure directly correlated with attrition decisions?

### Goal of the Dashboard
To deliver a dynamic visual reporting system that:
* Summarizes key HR workforce health indicators (Headcount, Attrition Count, Attrition Rate, Average Salary).
* Enables departmental and job-role cross-filtering to expose targeted retention risks.
* Equips HR leaders with visual evidence to refine promotion schedules, compensation packages, and work-life balance initiatives.

### Walkthrough of Key Visuals & Insights

* **Executive KPI Panel**:
  * Total Headcount: **1,480 Employees**
  * Total Attrition Count: **238 Employees**
  * Overall Attrition Rate: **16.08%**
  * Average Monthly Income: **$6,505**
  * Average Employee Age: **36.9 Years**
* **Attrition by Salary Slab & Income**: Visualizes turnover distribution across salary tiers (e.g., Upto 5k, 5k-10k) to determine compensation threshold risks.
* **Demographic & Role Analysis**: Breaks down turnover by `AgeGroup`, `Gender`, `Department` (R&D, Sales, HR), and specific `JobRole` profiles.
* **Satisfaction & Work-Life Factors**: Evaluates correlation between `JobSatisfaction`, `EnvironmentSatisfaction`, `WorkLifeBalance`, `OverTime`, and employee departure rates.
* **Tenure & Promotion Matrix**: Tracks years spent in current role versus years since last promotion to highlight stagnation risks.

### Business Impact & Insights

* **Targeted Retention Strategies**: Highlights high-risk demographics and salary tiers, enabling proactive intervention before valuable talent departs.
* **Compensation Adjustment**: Informs salary benchmarking for job roles experiencing disproportionate turnover due to pay structure gaps.
* **Managerial & Work-Life Policy**: Identifies teams with high overtime or low satisfaction metrics to adjust workload distribution and improve workplace environment.

---

## How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/hr-analytics-attrition-dashboard.git](https://github.com/YOUR_USERNAME/hr-analytics-attrition-dashboard.git)
