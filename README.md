# Data-Analysis-HR-Dashboard (MySQL Workbench,Power BI)
## Project Objective
The main objective is understand about HR employee among different states and categorized them under gender and who currently working and who terminated since 2000 to 2020.

## Dashboard 
![Screenshot (2)](https://github.com/user-attachments/assets/a055c86b-e55e-4a33-b5eb-f6b0c59b5249)

## Data Used
_Dataset_ - [Human Resources.csv](https://github.com/user-attachments/files/17524254/Human.Resources.csv) (HR data from the year 2000 to 2020).

_Data Cleaning & Analysis_ - MySQL Workbench

_Data Visualization_ - Power BI

## Questions
1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. How has the company's employee count changed over time based on hire and term dates?
11. What is the tenure distribution for each department?

## Summary of Dashboard
- The average length of employment for terminated employees is around 8 years.
- Most number of employees are male.
- Most number of employees works at the headquarters versus remotely.
- The net change of employees were increased day by day.When reached to the 2020 it's 96.4.
- Highest number of employees come from the state of Ohio.
- White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
- Considering about ages, there were 5 age groups created (18-24, 25-34, 35-44, 45-54, 55-64). Lot of employees were under age 25-34 and 35-44 while least number of employees under age 55-64.
- The youngest employee is 20 years old and the oldest is 57 years old.
- The average tenure for each department is about 8 years with Sales having the highest and Legal, Product, Training and Support having the lowest.
- The Auditing department has the highest turnover rate(0.18) and the least turn over rate(0.10) are in the Marketing, Business Development and Services departments.
- Engineering had the highest number of employees and Auditing had the lowest number of employees.
- Dashboard Interaction [HR_Employee Dashboard Report.pdf](https://github.com/user-attachments/files/17525681/HR_Employee.Dashboard.Report.pdf)
  
  ## Notice That 
  _! Some data were little bit different considering with other reports with same dataset file. Because of data cleaning.Here I used current date for calculations like birthday._

  ## Limitations
- Some records had wrong birthdates.Then there were negative ages and these were excluded during querying. Only used the 18 years old or above.
- Some termdates were far into the future and were not accept as correct data and not included in the analysis. Only used term dates those were less than or equal to current date.
 
  ## Final Conclusion
Highlights key trends in employee performance, turnover rates, average tenure and satisfaction levels. And this dashboard provides actionable insights for management, facilitating informed decision-making and strategic planning to enhance workforce engagement and retention. Data-driven strategies are essential for continuous improvement.



