This project demonstrates various SQL operations, including creating tables, inserting data, updating records, and running various queries on an employee, department, and company database. 
The SQL scripts cover a range of tasks, from basic CRUD operations to more complex queries for data analysis.

## Project Overview

This project involves the following tasks:
1. Creating tables for employees, departments, and companies.
2. Inserting data into the respective tables.
3. Performing various queries to retrieve, update, and delete data.
4. Handling complex queries involving conditions, limits, and the use of multiple operators.

### Database Schema

- **Employee Table**:
  - `id`: Employee ID (Primary Key, Auto Increment)
  - `name`: Employee Name
  - `city`: Employee's City
  - `department_id`: Foreign Key referencing the Department table
  - `salary`: Employee Salary
  
- **Department Table**:
  - `id`: Department ID (Primary Key, Auto Increment)
  - `name`: Department Name
  
- **Company Table**:
  - `id`: Company ID (Primary Key, Auto Increment)
  - `name`: Company Name
  - `revenue`: Company's Revenue
