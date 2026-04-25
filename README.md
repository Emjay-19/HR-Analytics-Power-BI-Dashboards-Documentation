# HR-Analytics-Power-BI-Dashboards-Documentation
## Project Overview

This project analyzes workforce data to understand employee composition, retention risks, and career progression. The dashboard provides insights into demographics, attrition patterns, and promotion readiness to support better HR decision-making.

## Data Source

The dataset contains employee records, including demographics (age, gender, marital status), job details (role, department, level), performance ratings, job satisfaction, salary bands, and attrition status.

## Problem Statement

Organizations often struggle with high employee turnover, unclear promotion pathways, and uneven workforce distribution. This project aims to identify key drivers of attrition, evaluate retention risks, and assess employee readiness for career growth.

## Tools and Methodology
Tools: Power BI (for visualization)
Methodology:
Aggregation and grouping (department, job role, salary band)
Exploratory Data Analysis (EDA)
Dashboard creation with interactive filters

## Data Preparation Process (Before Dashboard Design)
Before building the dashboards in Power BI, several data preprocessing steps were performed to prepare the dataset for analysis and visualization.  
**1. Converting Text Data into Structured Columns**  
The original dataset was in text format. Excel shortcut ALT + A + E (Text to Columns) was used to split the data into properly structured columns for easy import into Power BI.

**2. Additional Columns Created for Analysis:** To enhance insights and enable more advanced calculations, the following new columns were added;
- Salary Band – grouped employees into salary ranges.
- Age Band – categorized employees by age groups.
- Distance Category – grouped commute distance into buckets.
- Retention Risk Score – scored employees based on likelihood of attrition.
- Promotion Eligibility – identified employees eligible for promotion based on predefined criteria.  
These new columns enriched the dataset and improved segmentation in all three dashboards.


**3. DAX Measures Used in the Dashboards**
- Custom DAX formulas were created in Power BI to support interactive analytics:
- Total Attrition – counts number of employees marked as "Attrition = Yes".
- Attrition Rate – percentage of employees who left compared to total workforce.
- Eligibility Rate – percentage of employees eligible for promotion.
- Eligible Employees – total count of eligible employees.


## 📊 Dashboard 1: Workforce Composition Dashboard
**Purpose:** Provides a holistic view of the organization’s workforce structure, demographics, and distribution across departments.  

<img width="604" height="339" alt="Screenshot 2025-12-11 202758" src="https://github.com/user-attachments/assets/416cb117-2b86-48e7-9c87-8008240d174d" />


**Key Features**
- Total employee count and headcount distribution
- Gender and diversity breakdown
- Age band and experience segmentation
- Salary band and department-level workforce distribution

**Key Insights**  
- Workforce is unevenly distributed across departments, highlighting potential staffing imbalances.
- Majority of employees fall within specific age and salary bands, indicating a concentrated workforce segment.
- Diversity ratios vary significantly by department.

**Why It Matters**  
- Helps HR leaders understand workforce composition at a glance
- Supports fair workforce planning and diversity initiatives
- Enables data-driven headcount and compensation decisions

**Opportunities Identified**  
- Rebalance workforce across understaffed departments
- Improve diversity representation in departments with low ratios
- Plan succession strategies based on age and experience bands


## 📉 Dashboard 2: Attrition & Retention Risk Dashboard
**Purpose**  
Analyzes employee attrition patterns and identifies employees at risk of leaving the organization.

<img width="608" height="341" alt="Screenshot 2025-12-11 112403" src="https://github.com/user-attachments/assets/ccbded03-387e-494d-a1e3-427d1c2de96f" />


**Key Features**  
- Total attrition and attrition rate
- Attrition breakdown by age band, salary band, and department
- Retention risk score segmentation
- Attrition trend analysis

**Key Insights**  
- Attrition is higher among specific age and salary bands
- Certain departments show consistently higher retention risk scores
- Employees with longer commute distances exhibit higher attrition risk

**Why It Matters**  
- Attrition directly impacts productivity and hiring costs
- Early identification of at-risk employees enables proactive retention strategies
- Supports evidence-based HR interventions

**Opportunities Identified**  
- Introduce targeted retention programs for high-risk employee groups
- Review compensation and benefits for vulnerable salary bands
- Implement flexible or remote work options for long-distance commuters

**DAX Measures Used**  
- Total Attrition
- Attrition Rate


## 📈 Dashboard 3: Promotion & Career Progression Dashboard
**Purpose**  
Evaluates employee promotion readiness and career advancement opportunities within the organization.

<img width="601" height="340" alt="Screenshot 2025-12-11 112554" src="https://github.com/user-attachments/assets/1214bd72-33a4-4f00-882b-bedd576fa8a8" />

**Key Features**  
- Promotion eligibility overview
- Eligible employees by department and role
- Eligibility rate across age and salary bands
- Career progression insights

**Key Insights**  
- Promotion eligibility is concentrated within specific departments
- Some high-performing employees are not promotion-eligible, indicating potential policy gaps
- Eligibility rates vary significantly across age and salary bands

**Why It Matters**  
- Career growth is a key driver of employee retention
- Ensures transparent and fair promotion processes
- Helps leadership plan talent pipelines

**Opportunities Identified**  
- Review promotion criteria for inclusivity and fairness
- Develop targeted career development programs
- Strengthen internal mobility and succession planning

**DAX Measures Used**  
- Eligible Employees
- Eligibility Rate

## Key Analysis Findings
Total employees: 1,470
Attrition count: 237 (16%)
Gender distribution: 60% Male (882), 40% Female (588)
Majority age group: 26–35 (606 employees, ~41%)
Entry-level roles dominate: Level 1 & 2 = 1,077 employees (~73%)
Highest attrition by department:
Research & Development: 133 employees (~56% of total attrition)
Salary impact:
Employees earning 2001–5000 account for 145 attritions (~61%)
Retention risk:
Low risk: 865 employees (~59%)
Medium risk: 324 employees (~22%)
High risk: 281 employees (~19%)
Promotion readiness:
Only 82 employees (~5.6%) are eligible for promotion

**Limitations**
- Dataset may not include external factors like economic conditions or competitor influence
- Limited behavioral/qualitative data (e.g., employee feedback)
- Static snapshot; does not capture real-time workforce changes
- Some metrics (e.g., satisfaction scores) may be subjective

**Recommendations**
- Focus on reducing attrition in Research & Development through engagement strategies
- Review compensation for mid-salary employees (2001–5000 range)
- Improve career growth opportunities, as only 5.6% are promotion-ready
- Strengthen retention plans for high-risk employees (~19%)
- Balance workforce structure by developing higher-level talent

**Conclusion**

The analysis highlights key workforce challenges, including moderate attrition (16%), limited promotion readiness, and concentration of risk in specific departments. By addressing these areas, organizations can improve employee retention, enhance performance, and build a more sustainable talent pipeline.
