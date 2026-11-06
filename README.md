HR ANALYTICS
DASHBOARD PROJECT
Student Assignment Sheet • Beginner to Intermediate
Objective Build an interactive HR dashboard to understand workforce size, employee
attrition, salary patterns, and department-level trends.
Tools Power BI, Tableau, or Excel. Optional preparation using Python/Pandas or SQL.
Suggested time 4–8 hours, depending on the tool and student experience.
1. Dataset download
Recommended dataset: IBM HR Analytics Employee Attrition & Performance. It includes employee attributes
such as department, job role, age, income, years at the company, and attrition.
Download link: Kaggle — IBM HR Analytics Employee Attrition & Performance
Note: Kaggle may ask you to sign in. Download the CSV file and keep an unchanged copy of the original data.
2. Dashboard requirements
Create one dashboard page with these visuals and interactive controls:
Element What to show
KPI cards Total employees, attrition count, attrition rate, average monthly income, average years
at company
Bar chart Employee count and attrition by department
Bar chart Attrition by job role
Column chart Attrition by age group or years-at-company band
Donut / stacked bar Attrition split by overtime, gender, or business travel (choose an appropriate field)
Histogram / column chart Monthly income distribution or income by job level
Slicers / filters Department, job role, age group, overtime, business travel
HR Analytics Dashboard Project Page 2
3. Student tasks
01 — Load and inspect
Import the CSV. Identify the number of rows and columns, data types, and meaning of the key fields.
02 — Clean the data
Check missing values, duplicate rows, inconsistent category labels, and incorrect data types. Document any
changes.
03 — Create useful fields
Create an age group and a tenure group from Age and YearsAtCompany. Use clear, non-overlapping ranges.
04 — Calculate KPIs
Calculate total employees, attrition count, attrition rate, average monthly income, and average tenure.
05 — Analyze departments
Compare headcount and attrition rate across departments. Identify the department with the highest rate.
06 — Analyze job roles
Rank job roles by attrition count and attrition rate. Explain why counts and rates may tell different stories.
07 — Explore possible patterns
Compare attrition for overtime vs. no overtime, business travel groups, age groups, and tenure groups.
08 — Analyze income
Compare average monthly income by job level or department. Check whether income alone explains attrition;
avoid claiming causation.
09 — Build the dashboard
Arrange KPI cards and charts clearly. Add slicers, meaningful titles, data labels where useful, and consistent
formatting.
10 — Write recommendations
Write 3–5 evidence-based observations and recommendations for HR. Include the numbers that support each
point.
4. KPI definitions
KPI Definition
Total employees Count of employee records (or distinct EmployeeNumber if appropriate).
Attrition count Number of records where Attrition = Yes.
Attrition rate (Attrition count ÷ total employees) × 100.
Average monthly income Average of MonthlyIncome; specify the currency is not provided by the dataset.
Average tenure Average of YearsAtCompany.
5. Submission checklist
■ Cleaned dataset or documented cleaning steps
■ Dashboard file (PBIX, Tableau workbook, or Excel file)
■ Screenshot or PDF export of the dashboard
■ A short summary of 3–5 findings
■ Three practical HR recommendations supported by the data
6. Evaluation rubric (100 points)
HR Analytics Dashboard Project Page 3
Criteria Points
Data inspection and cleaning 15
Correct KPI calculations 20
Useful and accurate charts 20
Filters and dashboard usability 15
Insights and recommendations 20
Presentation and documentation 10
Important: This dataset is commonly used for learning and is not a representative sample of every workforce. Treat findings as
descriptive patterns, protect employee privacy, and do not use the analysis to make individual employment decisions.