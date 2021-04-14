# Employee Database: A Mystery in Two Parts

## Background
Perform a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

Design tables to hold data in the CSVs, import the CSVs into a SQL database.  Perform:

In this assignment, you will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, you will perform:

1. Data Modeling
2. Data Engineering
3. Data Analysis

## Technologies Used
- PostgreSQL
- Jupyter Notebook
- Python

## Objectives

#### Data Modeling

Inspect the CSVs and sketch out an ERD of the tables. 
![ERD](images/QuickDBD-EmployeeSQL.png)

#### Data Engineering

* Use the information you have to create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.

* Import each CSV file into the corresponding SQL table.

![Table](images/table.png)

#### Data Analysis

Once you have a complete database, do the following:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

![Analysis](images/analysis.png)

### Copyright

Alex Arnold © 2020. All Rights Reserved.
