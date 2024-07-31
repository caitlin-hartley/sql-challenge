# sql-challenge

Research project about people who a company employed during the 1980s and 1990s
Tasks: 

[Data Modeling](README.md#data-modeling)
  * Create Entity Relationship Diagram (ERD)
    
[Data Engineering](README.md#data-engineering)
  * Design tables to hold the data from the CSV files
  * Import the CSV files into a SQL database

[Data Analysis](README.md#data-analysis)
  * Perform analysis on the data

---

## Data modeling:

Created entity relationship diagram to understand the relationships between different tables

Set primary keys, foreign keys to link tables, and composite keys where there was not a unique identifier

![erd](https://github.com/caitlin-hartley/sql-challenge/blob/main/employeeSQL/employees_erd.png)

---

## Data Engineering

Created tables with required columns set to the correct data type, Primary Keys set for each table, Foreign keys set to relate tables, NOT NULL condition on necessary columns, and defined value lengths for each column

![create_tables](https://github.com/caitlin-hartley/sql-challenge/blob/main/images/table_creation.png)

---

## Data Analysis

Analyzed data for following outputs:
 * Employee number, last name, first name, sex, and salary of each employee
 * First name, last name, and hire date for the employees who were hired in 1986
 * Manager of each department along with their department number, department name, employee number, last name, and first name
 * Department number for each employee along with that employee’s employee number, last name, first name, and department name
 * First name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B
 * Each employee in the Sales department, including their employee number, last name, and first name
 * Each employee in the Sales and Development departments, including their employee number, last name, first name, and department name
 * Frequency counts, in descending order, of all the employee last names

![data_analysis](https://github.com/caitlin-hartley/sql-challenge/blob/main/images/data_analysis.png)

### Example of query and output for the employees in the sales and development departments:

QUERY:

![query](https://github.com/caitlin-hartley/sql-challenge/blob/main/images/employees_sales_development.png)

OUTPUT:

![output](https://github.com/caitlin-hartley/sql-challenge/blob/main/images/sales_development_output.png)
