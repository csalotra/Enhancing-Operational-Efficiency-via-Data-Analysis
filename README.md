# Enhancing-Operational-Efficiency-via-Data-Analysis

# Challenge Statement

Given the looming economic recession in the current year, Epoch systems, a Winnipeg based publicly traded company, which specializes in the manufacture of drones has decided to re-evaluate its entire cost structure in a bid to maintain the current level of its share value and meet investor expectations. 
After multiple meetings with various stakeholders, management decided that it will embark on a cost cutting exercise shifting focus to become more operationally efficient. Management has decided that a large component of the cost cutting will have to come from layoffs of its workforce. 
As a data analyst within Epochs data office - a team under the Development department, you have been instructed by your manager to investigate Epoch’s employee database and retrieve certain information that will enable management to take a more data driven approach to decision making. 
The employee database consists of six tables in total. These include the following: 
1.	Departments table: consists of a department number and department name. 
2.	Departments-employee table consists of the employee number, department number of employee and the start and end dates of the employees’ time at the department. 
3.	Departments-manager table consists of the employee number, department number of employee and the start and end dates of the employees’ time at the department for all managers. 
4.	Employee table: primary employee table which consists of employee number, birth date, first name, last name, gender, and hire date. 
5.	Salaries table: contains employee number, annual salary, from date and to date. 
6.	Title table: contains employee number, employee role/title, start date and end date of role. 
All current employees have a to_date column value of ‘9999-01-01’ to indicate that the termination date is unknown. 
Based on management discussions, the questions below will enable Epoch’s management to make better decisions about where some trimming of work force can be done. 
What is the total head count of all current employees at Epoch systems? 
What is the distribution of head count for current employees across the various departments? 
What is the average salary of all current employees by department? What is the max salary of all current employees by department? 
What is the count of current employees who are aged 70 and above distributed by departments? 
What is the average salary for employees grouped by titles? 
What is the head count of current employees grouped first by department and then by titles? 
Your task is to retrieve the data from the database that answers the questions above. Provide the results in a short report.
