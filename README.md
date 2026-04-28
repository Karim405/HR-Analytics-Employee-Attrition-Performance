# HR Employee Attrition Analytics Dashboard

---

## Project Overview
Employee attrition is one of the most expensive hidden challenges facing HR departments. Frequent employee turnover increases recruitment costs, onboarding expenses, training investments, and leads to the loss of organizational knowledge and productivity.

In this project, I developed a complete end-to-end HR Analytics solution to help management understand:

- Why employees are leaving
- Which departments and job roles are most affected
- How salary, satisfaction, age, and tenure influence attrition
- What retention actions HR managers should prioritize

The final deliverable is a fully interactive and business-driven Power BI Dashboard designed to support strategic workforce retention decisions.

---

## Business Problem
The HR department lacked a centralized reporting solution capable of monitoring employee turnover patterns in real time. Traditional spreadsheet reporting made it difficult to answer critical questions such as:

- Which department has the highest attrition rate?
- Are highly paid employees more likely to stay?
- Does employee tenure reduce turnover risk?
- Which job roles contribute most to total resignations?
- How do education, gender, and age affect employee retention?

Without this visibility, HR managers were unable to build proactive retention strategies.

---

## Project Objectives
This project was built to achieve the following analytical goals:

- Measure the overall employee attrition rate
- Identify high-risk departments and job roles
- Analyze the relationship between compensation and turnover
- Understand demographic factors affecting resignations
- Detect patterns between tenure, salary hike, training frequency, and employee departure
- Design an executive-level dashboard for fast HR decision making

---

## Data Source
The dataset used in this project is the IBM HR Analytics Employee Attrition Dataset collected from Kaggle.

- **Source:** IBM HR Analytics Dataset
- **Rows:** 1,470 Employee Records
- **Columns:** 35 HR Attributes
- **Domain:** Human Resources / Workforce Analytics

The dataset includes employee demographics, salary data, job satisfaction, work-life balance, education, performance rating, department, job role, and attrition status.

---

## Project Workflow

### 1. Data Collection
The first step was gathering the raw HR dataset from Kaggle and reviewing all available employee attributes to understand the business meaning behind each column.

This stage focused on:

- Understanding categorical and numerical variables
- Identifying HR KPIs relevant for turnover analysis
- Mapping each column to potential business questions

---

### 2. Data Understanding & Initial Exploration
Before any visualization work, I performed a full exploratory review of the dataset to understand:

- employee distribution
- missing values
- duplicate records
- skewed numerical columns
- unusual salary behavior
- attrition imbalance patterns

This step helped define which variables would provide the strongest analytical value in the dashboard.

---

### 3. Data Cleaning & Preprocessing
A significant amount of effort was dedicated to improving data quality before visualization.

#### Cleaning tasks performed:

- Handled missing values in satisfaction-related columns
- Verified uniqueness of Employee IDs and removed duplicate records
- Corrected inconsistent data types in numeric HR fields
- Standardized categorical labels for clean reporting
- Applied formatting fixes for salary and percentage columns

#### Outlier Treatment:
Outliers were detected in important numerical features such as:

- MonthlyIncome
- TotalWorkingYears
- DistanceFromHome

using statistical inspection and distribution analysis to ensure that extreme values would not distort dashboard insights.

---

### 4. Feature Engineering & Feature Selection
Instead of visualizing all columns directly, I selected only the most decision-relevant features that contribute to HR retention analysis.

#### Selected analytical dimensions included:

- Department
- JobRole
- Age
- Gender
- Education
- YearsAtCompany
- MonthlyIncome
- PercentSalaryHike
- TrainingTimesLastYear
- Attrition
- Job Satisfaction Indicators

#### Additional engineered fields created:

- Age Group Buckets
- Salary Band Categories
- Active Employee Count
- Attrition Rate %
- Attrition Count
- Average Monthly Income KPI

This improved both dashboard clarity and executive readability.

---

### 5. Dashboard Wireframe Design (Figma Planning)
Before opening Power BI, I designed the initial dashboard interface in Figma to create:

- a professional executive layout
- visual consistency
- KPI placement strategy
- page navigation experience
- color hierarchy

This pre-design step helped me build a dashboard that is not only analytical, but also presentation-ready and user friendly.

---

### 6. Power BI Dashboard Development
After finalizing the cleaned dataset, I imported the prepared data into Power BI and developed a multi-page interactive dashboard including:

#### Dashboard Pages:
- Executive Overview
- Department Analysis
- Employee Profile Analysis

#### Power BI Development Tasks:
- Built relational data model
- Created DAX measures for KPIs
- Designed custom navigation panel
- Added slicers and cross-filtering interactions
- Applied business storytelling visuals
- Implemented KPI cards, treemaps, line charts, bar charts, and demographic visuals
- Added executive-friendly dark theme UI

---

## Key KPIs Developed

- Total Employees
- Active Employees
- Attrition Rate %
- Average Monthly Income
- Attrition Count by Department
- Attrition Count by Job Role
- Attrition by Gender
- Attrition by Years at Company
- Salary Distribution by Department

---

## Analytical Insights Generated

### 1. Sales Department has the highest attrition pressure
Despite not being the largest department, Sales shows the highest employee resignation ratio, indicating retention instability.

### 2. Sales Executive and Research Scientist roles contribute the highest number of exits
These two job roles alone represent a major portion of total attrition, making them critical retention targets.

### 3. Employee turnover is heavily concentrated in the early years
Most resignations occur within the first 1–10 years at the company, suggesting onboarding and early engagement issues.

### 4. Lower income groups show stronger resignation patterns
Employees in lower salary bands demonstrate a higher tendency to leave compared to higher compensated employees.

### 5. Male employees represent a slightly higher attrition share
This indicates a workforce composition trend worth further HR investigation.

---

## Business Impact of the Dashboard
This solution transforms static HR records into an actionable retention intelligence system.

HR managers can now:

- monitor turnover in real time
- identify vulnerable departments
- prioritize employee retention efforts
- support compensation decisions using data

The dashboard replaces manual Excel reporting with a centralized decision-making platform.

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Data Cleaning Techniques
- Outlier Detection
- Feature Engineering
- Figma
- Microsoft Power BI
- Power Query
- DAX Measures
- Data Visualization
- Business Dashboard Storytelling


