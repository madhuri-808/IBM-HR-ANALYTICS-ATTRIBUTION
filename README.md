💼 IBM HR Analytics Dashboard – Unified Mentor Virtual Internship
📘 Project Overview

This project is part of my Unified Mentor Virtual Internship (Project 2).
The goal of this project was to analyze the IBM HR Employee Attrition dataset and identify key factors that influence employee turnover and performance.

Using Python for data preprocessing and Power BI for visualization, I built an interactive dashboard that helps HR professionals understand attrition patterns and make data-driven decisions.

🧰 Tools & Technologies Used

Python: Pandas, NumPy, Matplotlib, Seaborn

Power BI: Data Modeling, DAX, KPIs, Filters & Slicers

Excel: Dataset verification and preprocessing

📊 Project Workflow
🔹 Step 1: Data Cleaning & Analysis (Python)

Imported and explored the IBM HR dataset

Handled missing values and removed unnecessary columns

Encoded the “Attrition” column (Yes/No → 1/0)

Performed EDA to identify patterns in age, salary, and job role

df['Attrition'] = df['Attrition'].map({'Yes': 1, 'No': 0})
df.groupby('Department')['Attrition'].mean().sort_values(ascending=False)

🔹 Step 2: Data Visualization (Power BI)

Built KPIs: Total Employees, Active Employees, Attrition Rate

Created dynamic visuals: Attrition by Department, Education, Gender, Salary Hike

Added filters (Department, Education Field, Marital Status) for interactivity

Designed an insight card showing the department with highest attrition

📈 Key Insights
Metric	Value
Total Employees	1,470
Attrition Rate	16%
Highest Attrition Department	Sales (21%)
Average Age	37 years
Average Monthly Income	$6,503
🎯 Outcome

✅ Built an end-to-end HR Analytics Dashboard integrating Python + Power BI.
✅ Derived insights to support HR retention strategies.
✅ Improved skills in data cleaning, DAX calculations, and visualization storytelling




📂 Project Files

HR Attribution.ipynb → Python data analysis notebook

cleaned_hr_attrition.csv → Processed dataset for Power BI

IBM_HR_Analytics_Dashboard.pbix → Power BI dashboard file

🏷️ Tags

#UnifiedMentor #VirtualInternship #Python #PowerBI #HRAnalytics #DataAnalytics #Dashboard #DataVisualization

W
