**Project Overview**
The IBM HR Attrition Analytics Dashboard is a two-page interactive dashboard developed in Looker Studio to analyze employee attrition, workforce composition, and the factors associated with employee turnover.

The dashboard provides a high-level HR overview on the first page and deeper attrition analysis on the second page using calculated fields and interactive filters. The analysis covers employee demographics, departments, job roles, business travel, age groups, income levels, job satisfaction, and gender.

The dataset contains 1,470 employees, of whom 237 have left the organization, resulting in an overall attrition rate of 16.1%. The dashboard also shows an average monthly income of 6,502.93 and an average employee age of 36.9.

Objectives:
- Analyze the overall employee attrition rate.
- Identify departments and employee groups with higher attrition.
- Understand workforce distribution across job roles and gender.
- Analyze the relationship between attrition and business travel.
- Examine attrition across age groups, income brackets, and job satisfaction levels.
- Compare attrition rates across departments and gender.
- Build interactive filters to support employee-level and segment-level exploration.

Tools Used:
- Looker Studio
- Google Sheets
- IBM HR Analytics Employee Attrition Dataset
- Calculated Fields
- Interactive Filters
- Data Visualization

Process:
1. Imported the IBM HR dataset into Google Sheets.
2. Connected the dataset to Looker Studio.
3. Created the HR Overview dashboard with KPI cards for total employees, employees who left, average monthly income, and average employee age.
4. Built visualizations for attrition split, department-level attrition, workforce by job role, gender distribution, and business travel.
5. Created calculated fields including:
   - Attrition Flag
   - Attrition Rate
   - Age Group
   - Income Bracket
   - Satisfaction Level
6. Developed a second page for advanced attrition analysis.
7. Built department-level, age-group, income-bracket, and job-satisfaction attrition analysis.
8. Created a Department × Gender attrition-rate table.
9. Added interactive filters for Department, Gender, OverTime, Job Role, Age Group, and Income Bracket.
10. Added navigation between the dashboard pages.

Key Insights:
- The overall employee attrition rate is **16.1%**, with 237 employees having left out of 1,470 employees. :contentReference[oaicite:1]{index=1}
- **Research & Development** has the highest number of employees who left, followed by **Sales**, while Human Resources has substantially fewer departures. :contentReference[oaicite:2]{index=2}
- The workforce is predominantly male, with the dashboard showing a **60% male and 40% female** distribution. :contentReference[oaicite:3]{index=3}
- Sales Executive is the largest workforce role in the role-distribution chart, followed by several technical and research-oriented roles. :contentReference[oaicite:4]{index=4}
- Department-level analysis shows that **Sales has an attrition rate of approximately 20.6%**, Human Resources about **19.0%**, and Research & Development about **13.8%**, compared with the company average of **16.1%**. :contentReference[oaicite:5]{index=5}
- The **18–25 age group has the highest attrition rate**, at approximately 35.8%, while the other age groups have substantially lower rates. :contentReference[oaicite:6]{index=6}
- Employees in the lowest income bracket show considerably higher attrition than employees in the higher income brackets. :contentReference[oaicite:7]{index=7}
- The lowest job-satisfaction category has the highest attrition rate, while the very-high satisfaction group has the lowest rate. :contentReference[oaicite:8]{index=8}
- The Department × Gender analysis shows noticeable differences within departments. For example, HR shows a higher attrition rate for female employees than male employees, while Sales has similar rates across the two genders. :contentReference[oaicite:9]{index=9}

Dashboard Pages:

Page 1 — HR Overview Dashboard
Provides a high-level view of employee count, attrition, income, age, department-level departures, workforce by role, gender distribution, and business-travel patterns.

Page 2 — Advanced Attrition Analysis
Provides deeper analysis using calculated fields and interactive filters to explore attrition across age groups, income brackets, job satisfaction, departments, and gender.
