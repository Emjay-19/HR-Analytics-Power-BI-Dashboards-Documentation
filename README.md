# HR-Analytics-Power-BI-Dashboards-Documentation
This repository contains three interactive HR analytics dashboards designed in Power BI. The dashboards focus on Workforce Composition, Attrition &amp; Retention Risk, and Promotion &amp; Career Progression. They are built to help HR teams and business leaders make data-driven decisions around people strategy, talent management, and organizational planning

## Data Preparation Process (Before Dashboard Design)
Before building the dashboards in Power BI, several data preprocessing steps were performed to prepare the dataset for analysis and visualization.
1. Converting Text Data into Structured Columns

The original dataset was in text format. Excel shortcut ALT + A + E (Text to Columns) was used to split the data into properly structured columns for easy import into Power BI.

2. Additional Columns Created for Analysis
To enhance insights and enable more advanced calculations, the following new columns were added:
Salary Band – grouped employees into salary ranges.
Age Band – categorized employees by age groups.
Distance Category – grouped commute distance into buckets.
Retention Risk Score – scored employees based on likelihood of attrition.
Promotion Eligibility – identified employees eligible for promotion based on predefined criteria.
These new columns enriched the dataset and improved segmentation in all three dashboards.

3. DAX Measures Used in the Dashboards
Custom DAX formulas were created in Power BI to support interactive analytics:
Total Attrition – counts number of employees marked as "Attrition = Yes".
Attrition Rate – percentage of employees who left compared to total workforce.
Eligibility Rate – percentage of employees eligible for promotion.
Eligible Employees – total count of eligible employees.

