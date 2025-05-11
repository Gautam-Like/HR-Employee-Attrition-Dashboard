This project involves building a comprehensive HR Attrition Dashboard using Microsoft Power BI.
The goal is to analyze employee attrition trends and help HR teams take data-driven actions to reduce turnover.

📁 Dataset Details
Total Records: ~1,470 employees

Features: Age, Gender, Department, Salary, Job Role, Education Field, Job Satisfaction, Environment Satisfaction, Attrition Status

Source: IBM HR Analytics Dataset (Kaggle)

⚙️ DAX Measures Created
Total Employees = COUNT(EmployeeID)

Attrition Count = CALCULATE(COUNT(EmployeeID), HR[Attrition] = "Yes")

Attrition Rate (%) = DIVIDE([Attrition Count], [Total Employees])

Avg Job Satisfaction = AVERAGE(HR[JobSatisfaction])

Avg Environment Satisfaction = AVERAGE(HR[EnvironmentSatisfaction])

📊 Visuals Used in Dashboard
Bar Chart – Employees by Department

Stacked Bar Chart – Attrition by Gender

Line Chart – Age Group vs. Attrition

Donut Chart – Gender Distribution

Stacked Column Chart – Salary Bucket vs. Attrition

Clustered Bar – Job Role vs. Satisfaction

💡 Key Insights
Highest attrition observed in Sales and R&D departments

26–30 age group shows the highest attrition

Employees with salary < ₹3000 have higher attrition

Gender Ratio: 60% Male, 40% Female

🎯 Business Impact / Conclusion
This dashboard gives HR deep visibility into employee attrition, allowing them to focus retention efforts on the most affected groups.
By targeting critical departments and demographics, companies can improve satisfaction and reduce costly turnover.

🛠️ Tools & Skills Used
Tools: Power BI, DAX

Skills: Data Cleaning, Data Visualization, KPI Calculation, Dashboard Design, Storytelling

