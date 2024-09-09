# Employee Management System

## Overview
The **Employee Management System** is a SQL-based project designed to manage employees, departments, and salaries within a company. It includes tables for departments, employees, and salary records, along with various SQL operations for querying and managing this data.

## Features
- Manage employee information including name, position, salary, and department.
- Track salaries paid to employees with historical records.
- Perform CRUD operations on departments, employees, and salaries.

## Table Structure
### Departments Table
Stores information about company departments:
- **id_department**: Unique identifier for the department.
- **name**: Department name.

### Employees Table
Stores employee details:
- **id_employee**: Unique identifier for the employee.
- **name**: Employee's name.
- **position**: Employee's job position.
- **salary**: Employee's salary.
- **id_department**: Foreign key linking to the department.

### Salaries Table
Records salary payments to employees:
- **id_salary**: Unique identifier for the salary record.
- **id_employee**: Foreign key linking to the employee.
- **date**: Date of salary payment.
- **amount**: Amount of the salary paid.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-management-system.git
