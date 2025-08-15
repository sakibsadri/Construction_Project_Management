# 🏗️ Construction Project Management Dashboard

![Dashboard Preview](https://github.com/sakibsadri/Construction_Project_Management/blob/main/Construction_Project_Management.png)

## 📌 Overview
This interactive **Construction Project Management Dashboard** provides a comprehensive view of ongoing and completed construction projects.  
It tracks **key performance indicators (KPIs)** such as budget utilization, task completion rates, profit trends, and project statuses to help stakeholders make informed decisions.

Built entirely in **Power BI**, this dashboard uses multiple **DAX measures** and calculated columns for accurate, real-time insights.

---

## 🎯 Key Features
- **KPI Summary Cards**:  
  - Total Projects  
  - Total Tasks  
  - Total Cost  
  - Total Budget  
  - Profit  

- **Performance Visuals**:  
  - **Monthly Trends**: Cost vs. Budget, Profit by Month  
  - **Task Analysis**: By Priority, Progress Group, Project Type  
  - **Project Status Distribution**: On Hold, Behind, On Track, Completed  
  - **Geographic Insights**: Projects by U.S. States  
  - **Project Manager Performance Table**: Cost, Budget, Profit, Task Completion %, Budget Utilization %

---

## ⚙️ Tools & Technologies Used
- **Power BI Desktop**
- **Power Query** for data transformation
- **DAX Measures** for calculations
- **Visual Types**: Line Chart, Column Chart, Pie Chart, Donut Chart, Map, Table

---

## 📊 Measures & Calculations (DAX Examples)
Some key DAX measures used:
```DAX
Budget Utilization % = DIVIDE(SUM(Cost), SUM(Budget)) * 100

Task Completion % = DIVIDE(SUM(CompletedTasks), SUM(TotalTasks)) * 100

Profit = SUM(Revenue) - SUM(Cost)

Cost vs Budget Variance = SUM(Budget) - SUM(Cost)
