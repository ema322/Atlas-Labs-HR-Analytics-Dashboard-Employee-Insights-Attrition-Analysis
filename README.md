# Atlas-Labs-HR-Analytics-Dashboard-Employee-Insights-Attrition-Analysis
An interactive Power BI HR analytics dashboard exploring employee demographics, performance, salary, marital status, department distribution, and attrition trends. Features KPI cards, dynamic filters, age and gender comparisons, and workforce insights to support data-driven HR decisions.





<img width="577" height="325" alt="Screenshot 2026-10-26 230428" src="https://github.com/user-attachments/assets/0948e69e-aaf8-496f-b0c0-58aa4f01b1c3" />
<img width="578" height="327" alt="Screenshot 2026-10-26 230507" src="https://github.com/user-attachments/assets/21413a3e-725b-425d-a841-4f5a1f2907db" />



# 📊 Atlas Labs HR Analytics Dashboard
### Workforce Analysis | Employee Demographics | Salary Insights | Attrition Analysis

---

## 📌 Project Overview

The **Atlas Labs HR Analytics Dashboard** is an interactive data analytics project developed using Microsoft Power BI to explore employee demographics, workforce distribution, salary patterns, and attrition-related indicators.

The dashboard transforms HR data into meaningful visualizations, allowing users to compare employee groups, monitor workforce metrics, and explore patterns across departments, job roles, age groups, genders, marital statuses, and ethnic groups.

This project demonstrates how business intelligence and data visualization can support Human Resources (HR) teams in understanding their workforce and making more informed, data-driven decisions.





## 🎯 Project Objectives

- Analyze employee demographics by age group and gender.
- Monitor active and inactive employees and attrition indicators.
- Compare workforce distribution across departments and job roles.
- Explore marital status and ethnic group distributions.
- Compare employee counts with average salary across ethnic groups.
- Provide interactive filtering for more focused HR analysis.
- Support data-driven workforce planning and HR decision-making.

**Business value:**  
This page gives HR teams a starting point for monitoring workforce changes and exploring employee retention patterns.

**Analysis and comparisons:**

- Compare male and female employee counts.
- Examine workforce distribution across age groups.
- Compare marital status categories by employee count and percentage.
- Compare employee representation across ethnic groups.
- Analyze differences in average salary between ethnic groups.

**Business value:**  
These comparisons help HR teams understand workforce composition, assess representation, and explore demographic differences in salary.

### 3. Performance Analysis

The dashboard navigation includes a Performance page for exploring employee performance indicators.

The available screenshots do not show this page's visualizations in sufficient detail to document specific metrics or conclusions.

Potential areas of analysis include:
- Employee performance indicators.
- Comparisons across departments and job roles.
- Workforce patterns that may support performance management.

*Document the actual metrics and visuals after adding a screenshot of the Performance page.*

### 4. Attrition Analysis

The dashboard navigation includes an Attrition page focused on employee turnover and retention.

Potential areas of analysis include:
- Attrition trends over time.
- Differences in attrition across demographic groups.
- Department and job-role comparisons.
- Identification of employee segments requiring further investigation.

*Confirm the actual visuals and measures on the Attrition page before documenting specific findings.*

## 🔍 Interactive Filters

The dashboard provides interactive filters for:

- **Gender** — analyze selected gender categories.
- **Department** — focus on specific departments.
- **Age** — explore employee groups by age.

These filters allow users to refine their analysis and investigate differences between workforce segments.

## 📈 Key Observations from the Available Screenshots

The following observations describe the displayed visuals and should be validated against the underlying dataset and DAX measures.

1. **Workforce distribution over time:** The yearly stacked column chart displays total values ranging from 106 to 155 across the years shown, with the highest displayed total in 2022.

2. **Department and job-role distribution:** The Overview page breaks active employees down by department and then by job role, allowing users to explore workforce allocation.

3. **Gender and age distribution:** The Demographic page displays 675 female employees and 651 male employees, alongside other gender categories. The chart also shows employee counts by age bin.

4. **Marital status comparison:** The donut chart compares married, single, and divorced employee groups, showing both counts and percentages.

5. **Ethnic group and salary comparison:** The combined chart compares employee counts with average salary across ethnic groups, making differences in representation and average salary easier to explore.

## 💡 Business Insights & Applications

This dashboard can help HR teams:

- Monitor workforce composition and employee status.
- Compare demographic groups and employee distributions.
- Explore department and job-role staffing patterns.
- Examine attrition indicators and investigate potential retention challenges.
- Compare average salaries across employee groups.
- Make more informed decisions about workforce planning and further HR analysis.

The dashboard highlights patterns for investigation; it does not establish the causes of attrition or salary differences on its own.

## 📁 Repository Structure

```text
Atlas-Labs-HR-Analytics/
│
├── README.md
├── Dashboard/
│   └── Atlas_Labs_HR_Analytics.pbix
├── Screenshots/
│   ├── Overview.png
│   └── Demographic.png
└── Data/
    └── Source_Data.xlsx
```

*Replace the example filenames with your actual uploaded files. Include source data only if you have permission to share it.*


## 1️⃣ Overview Dashboard

The Overview page provides a high-level summary of the workforce, employee activity, and attrition-related metrics.

### 📌 Key Performance Indicators (KPIs)

| KPI | Displayed Value | Purpose |
|---|---:|---|
| Active Employees | 237 | Displays the active employee count shown in the screenshot |
| Attrition Rate | 84% | Displays the attrition indicator; the formula requires validation |
| Total Employees | 1K | Shows the rounded total displayed on the Overview page |
| Inactive Employees | 1,233 | Displays the inactive employee count shown in the screenshot |

### 📊 Visualization 1: Total Employee Trend by Year

The stacked column chart displays yearly totals from 2012 through 2022, with two colored segments representing separate employee-related measures.

**Analysis performed:**

- Compared the displayed yearly totals.
- Examined differences between the two segments in each year.
- Identified the highest and lowest displayed annual totals.
- Explored how the distribution changes across the selected years.

**Visible observations:**

- The highest displayed total is 155 in 2022.
- The lowest displayed total is 106 in 2017.
- The displayed totals vary across the period rather than increasing consistently.

**Business value:**

Yearly comparisons help HR teams investigate changes in workforce activity and understand whether the underlying employee measures are changing over time.

> Note: Confirm the exact meaning of the two stacked measures and whether these values represent hires, attrition, or another employee metric before interpreting the chart as a headcount trend.

### 📊 Visualization 2: Active Employees by Department and Job Role

The hierarchical visualization breaks down active employees by department and then by job role.

**Analysis performed:**

- Explored the distribution of active employees across departments.
- Compared the visible department-level employee counts.
- Examined the job-role breakdown within the displayed departments.
- Identified larger and smaller workforce segments.

**Visible observations:**

- The chart displays 237 active employees in total.
- Technology is displayed with 133 employees.
- Sales is displayed with 92 employees.
- Human Resources is displayed with 12 employees.

These displayed department counts sum to 237.

**Business value:**

This comparison helps HR teams explore workforce allocation and identify departments or roles that may require closer staffing analysis.

---

## 2️⃣ Demographic Analysis Dashboard

The Demographic page examines the composition of the workforce across age, gender, marital status, and ethnic groups.

### 📌 KPI Cards: Youngest and Oldest Employees

| KPI | Displayed Value | Purpose |
|---|---:|---|
| Youngest Employee | 18 | Displays the minimum employee age |
| Oldest Employee | 51 | Displays the maximum employee age |

**Business value:**

These indicators provide a quick overview of the age range represented in the displayed dataset.

### 📊 Visualization 1: Total Employees by Gender and Age Bins

This hierarchical visualization compares gender categories and their distribution across age groups.

**Displayed gender counts:**

| Gender Category | Employee Count |
|---|---:|
| Female | 675 |
| Male | 651 |
| Non-Binary | 124 |
| Prefer Not to Say | 20 |
| **Total** | **1,470** |

**Analysis performed:**

- Compared employee counts across gender categories.
- Examined age groups including under 20, 20–29, 30–39, 40–49, and over 50.
- Explored how employee representation varies across age categories.
- Used hierarchical drill-down to investigate demographic groups.

**Visible observations:**

- Female employees are the largest displayed gender category, with 675 employees.
- Male employees account for 651 employees.
- The displayed female count exceeds the male count by 24 employees.
- Non-binary employees account for 124 employees.
- Twenty employees selected the "Prefer Not to Say" category.

**Business value:**

Demographic comparisons help HR teams understand workforce composition and support fair, evidence-based workforce planning.

### 📊 Visualization 2: Total Employees by Marital Status

The donut chart compares employee distribution across marital status categories.

| Marital Status | Displayed Count | Displayed Percentage |
|---|---:|---:|
| Married | 624 | 42.45% |
| Single | 549 | 37.35% |
| Divorced | 297 | 20.20% |
| **Total** | **1,470** | **100%** |

**Analysis performed:**

- Compared the number of employees in each marital status category.
- Examined the percentage contribution of each category.
- Identified the largest and smallest groups.
- Compared the distribution of marital statuses across the workforce.

**Visible observations:**

- Married employees represent the largest category at 42.45%.
- Single employees represent 37.35%.
- Divorced employees represent 20.20%.

**Business value:**

This visualization summarizes the workforce's marital status distribution and supports descriptive demographic reporting.

### 📊 Visualization 3: Total Employees and Average Salary by Ethnic Group

The combined chart compares employee counts with average salary across ethnic groups.

**Categories displayed:**

- White
- Black or African American
- Mixed or multiple ethnic groups
- Asian or Asian American
- American Indian or Alaska Native
- Native Hawaiian
- Other

**Measures compared:**

1. Total employees in each ethnic group.
2. Average salary for each ethnic group.

**Analysis performed:**

- Compared workforce representation across ethnic groups.
- Examined differences in average salary.
- Identified groups with relatively high or low displayed employee counts.
- Compared salary patterns alongside employee representation.

**Visible observations:**

- White employees form the largest displayed group, with 860 employees.
- Black or African American employees account for 207 employees.
- Mixed or multiple ethnic groups account for 198 employees.
- Asian or Asian American employees account for 113 employees.
- American Indian or Alaska Native employees account for 50 employees.
- Native Hawaiian employees account for 26 employees.
- The Other category accounts for 16 employees.

The chart also displays average salary labels ranging approximately from $101.7K to $115.3K.

**Business value:**

This comparison makes it easier to investigate differences in workforce representation and average salary across ethnic groups. Such comparisons are descriptive and do not establish the reasons behind salary differences.

---

## 3️⃣ Performance Analysis Dashboard

The navigation menu includes a Performance page, but its detailed visuals are not visible in the supplied screenshots.

This page can be documented further once its actual charts and KPIs are available.

Potential areas to describe, if included in the dashboard, are:

- Employee performance indicators.
- Performance comparisons across departments and job roles.
- Differences between employee groups.
- Relationships between workforce characteristics and performance metrics.

Any final findings should be based on the actual measures and visualizations on this page.

---

## 4️⃣ Attrition Analysis Dashboard

The navigation menu also includes a dedicated Attrition page.

The Overview page displays an attrition-related KPI and a yearly stacked chart, but the screenshots do not show enough detail to confirm all calculations or the complete Attrition page.

Further analysis may include, if supported by the dashboard:

- Employee attrition trends over time.
- Attrition differences across departments.
- Attrition comparisons by age and gender.
- Job roles with different attrition patterns.
- Potential workforce retention challenges.

These comparisons can help HR teams identify patterns that merit investigation. Additional data is required to establish why employees leave.

---

# 🎛️ Interactive Dashboard Features

## Available Filters

The screenshots show three filters on the left navigation panel.

| Filter | Function |
|---|---|
| Gender | Filters employee data by gender category |
| Department | Filters the dashboard by department |
| Age | Filters employee data by age |

### Benefits of Interactive Filtering

- Enables focused analysis of specific employee groups.
- Supports comparisons between demographic segments.
- Helps users investigate department-level differences.
- Makes the dashboard more flexible for different HR questions.
- Improves the accessibility of workforce information.

The exact behavior of each filter depends on the Power BI visual interactions configured in the report.

---

# 💡 Key Business Insights

Based on the visible dashboard values, several initial observations can be made.

### 1. Workforce Demographics

The Demographic page displays 1,470 employees, with female employees representing the largest displayed gender category.

### 2. Department Distribution

The Overview page displays 237 active employees distributed across Technology, Sales, and Human Resources. Technology represents the largest displayed department group.

### 3. Marital Status

Married employees represent 42.45% of the displayed workforce, followed by single employees at 37.35%.

### 4. Ethnic Group Representation

The White category has the highest displayed employee count. Comparing employee counts with average salary provides a starting point for further workforce analysis.

### 5. Yearly Comparisons

The yearly chart displays variation in totals between 2012 and 2022. The underlying measures should be confirmed before drawing conclusions about hiring, attrition, or overall workforce growth.

### 6. Attrition Monitoring

The Overview page places employee activity and an attrition-related indicator together, helping users begin investigating workforce retention. The attrition formula should be validated before using the percentage for business decisions.

---

# 📐 Data Quality & Validation

Reliable analytics depends on consistent measures and accurate reporting.

Before publishing the dashboard, validate the following:

- **Employee totals:** The Overview page shows approximately 1K total employees, while the Demographic page shows 1,470. Confirm whether these pages use different filters, populations, or measures.
- **Active and inactive employees:** The Overview values should be reconciled with the total employee count and the definitions used in the data model.
- **Attrition rate:** Confirm the DAX formula, numerator, denominator, and intended reporting period.
- **Yearly chart:** Confirm the definitions of both stacked measures.
- **Salary measures:** Verify the currency, aggregation, and average salary calculation.
- **Demographic percentages:** Ensure the category counts and percentages use the same population and filter context.

These checks are important before presenting the dashboard's findings as confirmed business results.

---

# 🚀 How to Access the Project

1. Clone or download this GitHub repository.
2. Install Microsoft Power BI Desktop.
3. Open the `.pbix` dashboard file.
4. Update the source file path if the dataset is stored locally.
5. Refresh the data model if the source data is available.
6. Navigate through the dashboard pages.
7. Apply filters to explore workforce patterns and compare categories.

**Note:** The project will only refresh successfully if the necessary data sources, permissions, and connections are available.

---

# 📂 Suggested Repository Structure

```text
Atlas-Labs-HR-Analytics/
│
├── README.md
│
├── Dashboard/
│   └── Atlas_Labs_HR_Analytics.pbix
│
├── Screenshots/
│   ├── Overview.png
│   └── Demographic.png
│
└── Data/
    └── Source_Data.xlsx
```

Replace the example filenames with your actual files. Include source data only when you have permission to publish it.

---

# 📚 Skills Demonstrated

- Power BI Dashboard Development
- Data Visualization
- HR Analytics
- KPI Reporting
- Demographic Analysis
- Salary Analysis
- Workforce Distribution Analysis
- Attrition Monitoring
- Interactive Report Design
- Business Insight Communication
- Data Validation and Quality Checks

---

# 👩‍💻 Author

**Emma Saleh**

Aspiring Data Analyst | Power BI | Excel | Data Visualization

This project is part of my data analytics portfolio and demonstrates my ability to transform workforce data into interactive visual reports and business-focused comparisons.

---

# ⭐ Conclusion

The Atlas Labs HR Analytics Dashboard provides an interactive overview of employee demographics, workforce distribution, salary patterns, and attrition-related indicators.

By combining KPI cards, demographic breakdowns, yearly comparisons, and interactive filters, the dashboard supports the exploration of workforce patterns and helps identify areas for further HR analysis.

The project demonstrates how data visualization can make HR information easier to interpret and support more informed, evidence-based decisions.

**If you find this project useful, feel free to explore the repository and share your feedback!**
