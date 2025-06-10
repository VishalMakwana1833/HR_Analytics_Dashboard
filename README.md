# HR_Analytics_Dashboard

##Project Objective
A comprehensive HR Analytics dashboard developed using Excel and Power BI to visualize key workforce metrics. Data cleaning and merging were performed with Python to ensure accuracy and consistency. The dashboard provides insights into employee demographics, attrition rates, performance trends, and recruitment effectiveness.

## DataSet Used
- <a href="https://github.com/VishalMakwana1833/HR_Analytics_Dashboard/blob/main/Merged_HR_Data.csv">HR Analytics Data</a>

## Question KPIs
- Total number of employees in the organization.
- Attrition Count
- Attrition Rate (%)
- Average Monthly Income
- Average total work experience in years.
- Compares attrition count across genders.
- Monthly Income Distribution (Attrition-based)
- Dashborad Interaction <a href="https://github.com/VishalMakwana1833/HR_Analytics_Dashboard/blob/main/HR_Analytics_Dashboard.jpg">HR Dashboard</a>

## Process
- Imported multiple HR-related datasets (HR_employee_data.csv, employee_years.csv etc.) using Pandas.
- Removed duplicates and handled null values using drop_duplicates() and fillna() for clean records.
- Exported the final cleaned and merged dataset to .csv for Power BI integration.
- Imported the cleaned dataset into Power BI and created relationships if needed.
- Created calculated columns & measures (e.g., Attrition Rate = DIVIDE([Attrition Count], [Total Employees])).

## Dashboard
![HR_Analytics_Dashboard](https://github.com/user-attachments/assets/a180dd9d-6475-4885-a8c1-7f1b032a5fa0)

## Project Insights
- Analyzed data of 1,470 employees to identify workforce trends, attrition patterns, and departmental performance using Python and Power BI.
- Discovered an overall attrition rate of 16.12%, with the Sales Executive and Research Scientist roles showing the highest employee exits.
- Found that the average work experience of employees is 11.28 years, and the average monthly income is ₹6.5K, aiding in compensation analysis.
- Enabled data slicing by Department, Gender, Job Role, and Education Field, allowing granular HR decision-making.

## Conclusion
The HR Analytics Dashboard provided critical insights into employee attrition patterns, income trends, and departmental performance, helping HR teams make informed, data-driven decisions.Analysis revealed that Sales Executives and Research Scientists had the highest attrition, and Research & Development faced the most exits by department, indicating the need for targeted retention strategies.The average employee was found to have 11+ years of experience and earn ₹6.5K/month, helping HR benchmark compensation and experience for hiring and retention planning.Overall, the dashboard empowered HR stakeholders to visualize workforce health, improve retention efforts, and align talent management strategies with business goals.


