# sql-challenge
This Challenge is divided into three parts: Data modelling, Data engineering, and Data analysis and the scenario behind the project is as follows-
You are the new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.
For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modelling, data engineering, and data analysis, respectively.

Data Modelling Part
Starts with Inspecting the CSV files, and then sketching an ERD of the tables to be created. To create the sketch QuickDBD is used.

Data Engineering Part
Used the provided information to create a table schema for each of the six CSV files. Did the following:
Specify the data types, primary keys, foreign keys, and other constraints.

Created the tables in the correct order to handle the foreign keys.

Imported each CSV file into its corresponding SQL table.

List the employee number, last name, first name, sex, and salary of each employee.

List the first name, last name, and hire date for the employees who were hired in 1986.

List the manager of each department along with their department number, department name, employee number, last name, and first name.

List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

List the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

List each employee in the Sales department, including their employee number, last name, and first name.

List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
