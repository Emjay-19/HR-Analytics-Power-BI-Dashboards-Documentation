# HR-Analytics-Power-BI-Dashboards-Documentation
This repository contains three interactive HR analytics dashboards designed in Power BI. The dashboards focus on Workforce Composition, Attrition &amp; Retention Risk, and Promotion &amp; Career Progression. They are built to help HR teams and business leaders make data-driven decisions around people strategy, talent management, and organizational planning

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
**Key Features:**
- Total employee count and headcount distribution
- Gender and diversity breakdown
- Age band and experience segmentation
- Salary band and department-level workforce distribution

**Key Insights**  
Workforce is unevenly distributed across departments, highlighting potential staffing imbalances.
Majority of employees fall within specific age and salary bands, indicating a concentrated workforce segment.
Diversity ratios vary significantly by department.

Why It Matters
Helps HR leaders understand workforce composition at a glance
Supports fair workforce planning and diversity initiatives
Enables data-driven headcount and compensation decisions
Opportunities Identified
Rebalance workforce across understaffed departments
Improve diversity representation in departments with low ratios
Plan succession strategies based on age and experience bands

Data Used
Employee ID
Gender, Age Band, Salary Band
Department
Job Role
Distance Category
Job Level

📉 Dashboard 2: Attrition & Retention Risk Dashboard
Purpose
Analyzes employee attrition patterns and identifies employees at risk of leaving the organization.

Key Features
Total attrition and attrition rate
Attrition breakdown by age band, salary band, and department
Retention risk score segmentation
Attrition trend analysis

Key Insights
Attrition is higher among specific age and salary bands
Certain departments show consistently higher retention risk scores
Employees with longer commute distances exhibit higher attrition risk

Why It Matters
Attrition directly impacts productivity and hiring costs
Early identification of at-risk employees enables proactive retention strategies
Supports evidence-based HR interventions

Opportunities Identified
Introduce targeted retention programs for high-risk employee groups
Review compensation and benefits for vulnerable salary bands
Implement flexible or remote work options for long-distance commuters

DAX Measures Used
Total Attrition
Attrition Rate

📈 Dashboard 3: Promotion & Career Progression Dashboard
Purpose
Evaluates employee promotion readiness and career advancement opportunities within the organization.
Key Features
Promotion eligibility overview
Eligible employees by department and role
Eligibility rate across age and salary bands
Career progression insights

Key Insights
Promotion eligibility is concentrated within specific departments
Some high-performing employees are not promotion-eligible, indicating potential policy gaps
Eligibility rates vary significantly across age and salary bands

Why It Matters
Career growth is a key driver of employee retention
Ensures transparent and fair promotion processes
Helps leadership plan talent pipelines

Opportunities Identified
Review promotion criteria for inclusivity and fairness
Develop targeted career development programs
Strengthen internal mobility and succession planning

DAX Measures Used
Eligible Employees
Eligibility Rate
