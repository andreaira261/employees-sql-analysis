# Employees SQL Challenge

## Overview 
In this assignment, a research project was conducted to analyze the individuals employed at a company during the 1980s and 1990s. An Entity Relationship Diagram (ERD) and table schemas were designed to represent the data in the data modeling phase. During the data engineering process, SQL was employed to translate the table schemas into database structures. Finally, the data was analyzed to extract valuable insights about employees, departments, and their relationships.

## Languages/ Tools: 
- Quick DBD
- SQL
- PostgreSQL
- pgAdmin

## Data Modeling
An Entity Relationship Diagram was designed using [Quick DBD](https://www.quickdatabasediagrams.com/) to represent all the tables from the dataset.
![employee_ERD](https://github.com/andreaira261/employees-sql-analysis/assets/48165713/e13e358e-f5dd-4186-b393-a60f643532ad)

## Data Engineering
File: EmployeeSQL → [employee_schema.sql](EmployeeSQL/employee_schema.sql)

Using the ERD created during the Data Modeling phase, a table schema was generated specifying the data types, primary keys, foreign keys, and other constraints. 

<img width="520" alt="data-modeling-1" src="https://github.com/andreaira261/employees-sql-analysis/assets/48165713/11ad23b3-c2b9-4274-b161-2e4d3df902d4">
<img width="710" alt="data-modeling-2" src="https://github.com/andreaira261/employees-sql-analysis/assets/48165713/f15453b3-78c4-46eb-946e-6ac9d4816213">


## Data Analysis 
File: EmployeeSQL → [employee_queries.sql](EmployeeSQL/employee_queries.sql)

The database, managed through PostgreSQL and monitored using pgAdmin, was analyzed using SQL queries to answer the following questions about the data:
  1. List the employee number, last name, first name, sex, and salary of each employee.
  2. List the first name, last name, and hire date for the employees who were hired in 1986.
  3. List the manager of each department along with their department number, department name, employee number, last name, and first name.
  4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
  5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
  6. List each employee in the Sales department, including their employee number, last name, and first name.
  7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
  8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

![data-analysis](https://github.com/andreaira261/employees-sql-analysis/assets/48165713/55807d20-3003-46ae-86db-a793a24fc3e7)



