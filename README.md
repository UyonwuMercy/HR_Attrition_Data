# HR_Data_Attrition

## Overview
This project repository is designed to analyze HR Attrition Data, offering insights into employee demographics, job satisfaction, and attrition trends. By leveraging Excel for data preparation and Power BI for advanced visualization, this project delivers actionable insights for HR teams to improve employee engagement and retention.

## Objectives
- Attrition Analysis: Examine factors contributing to employee attrition.
- Satisfaction Ratings: Evaluate employee and job satisfaction scores across roles and departments.
- Employee Demographics: Analyze demographic data (age, gender, marital status, educational field) to identify trends.
- Overtime Impact: Understand how overtime influences attrition rates.
- Departmental Overview: Summarize employee distribution and attrition by department.
  
## Project Structure
### Data Preparation and Cleaning (Excel

## Data Columns:

- Attrition: Indicates whether an employee has left the company.
- Business Travel: Frequency of business travel.
- CF_age_band: Age bands categorized for easy analysis.
- CF_Attrition Label: Label indicating attrition status (e.g., "Active," "Exited").
- Department: Department where the employee works.
- Educational Field: Employee's field of education.
- Employee Number: Unique identifier for each employee.
- Gender: Gender of the employee.
- Job Role: Employee's job role.
- Marital Status: Marital status.
- Overtime: Indicates whether the employee works overtime.
- CF_Current Employee: Current employment status.
- Employee Count: Total number of employees.
- Employee Satisfaction: Self-reported satisfaction score.
- Job Satisfaction Rating: Job-specific satisfaction rating, etc.

## Data Cleaning in Excel:
- Remove duplicates and empty rows.
- Ensure categorical data (e.g., Gender, Department) is consistent.
- Calculate new metrics as needed (e.g., attrition rate per department).
- Create additional columns as needed, like tenure in age bands.

### Data Analysis (Excel)
#### Key Metrics:
- Attrition rate per department, age band, and job role.
- Average job and employee satisfaction ratings.
- Distribution of employees by department, gender, and marital status.
- Formulas and Calculations:
- Attrition Rate: Calculate as =(Attrition Count/Total Employees) * 100.
- Satisfaction Averages: Use AVERAGEIF formulas for each satisfaction metric by job role and department.

### Data Transformation (Power BI)
- Import Data: Load cleaned data from Excel into Power BI.
- Data Modeling:
Create relationships between tables if using multiple sources (e.g., demographic data table linked to satisfaction metrics).
- Set up calculated columns or measures for metrics such as Attrition Rate, Average Satisfaction, and Employee Count.
  
## Visualization and Dashboard Creation (Power BI)
- Dashboard Elements:
- Attrition Overview:
- Attrition rate by department, age band, and gender.
- Visualizations: Bar charts for attrition rates, donut chart for attrition by gender, line chart for attrition over time.
- Satisfaction Analysis:
Job satisfaction and employee satisfaction by department and role.
- Visualizations: Heatmap for satisfaction scores, bar chart comparing departments.
- Employee Demographics:
Breakdown of employees by age band, marital status, educational field.
- Visualizations: Pie chart for marital status, stacked bar chart for educational field.
- Visualizations: Dual bar chart for overtime vs. non-overtime attrition.
- Interactive Slicers:
- Add slicers for Department, Age Band, Gender, Marital Status, and Job Role to enable users to filter data dynamically.
- Drill-down Options:
Allow drill-downs on visualizations to view department-specific or job role-specific attrition and satisfaction rates.

## Key Insights & Findings
- Attrition Trends:
- Identify which departments and roles experience the highest attrition, providing insights for HR intervention.
- Satisfaction Insights:
Highlight high and low satisfaction areas, helping HR teams identify roles or departments needing engagement strategies.
- Demographic Vulnerabilities:
Spot patterns in attrition based on age, marital status, or gender.
Impact of Overtime: 

## Visualization On Power BI
![Screenshot (70)](https://github.com/user-attachments/assets/ab984fe7-79e2-423f-9ceb-71fd70ae4c57)
![Screenshot (71)](https://github.com/user-attachments/assets/0e91332f-5ee6-484e-90db-cf7d5996c3e4)
![Screenshot (72)](https://github.com/user-attachments/assets/91b1aef0-5715-49c7-b03d-365515692e3d)

## Conclusion
This HR Data Attrition Repository enables data-driven decision-making in HR departments by providing comprehensive insights into employee attrition, satisfaction, and demographics. The Excel-prepared data, alongside interactive Power BI visualizations, offers a complete view of the organization's HR health, enabling informed actions to improve retention and engagement.
