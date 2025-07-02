# Mini SQL Project: Employee and Department Management

This project demonstrates basic SQL operations for managing employee and department data within a company database. It includes various types of SQL queries for data retrieval, manipulation, backup operations, and basic transactions. The project uses SQL queries for real-world scenarios, including querying employees, departments, and job histories, managing employee records, and performing data backup and restore operations.

## Project Overview

The project is structured around several SQL tables, including:
- **Employees**: Stores employee information such as name, email, job title, salary, and department.
- **Departments**: Contains data on company departments like name, manager, and location.
- **Jobs**: Holds information about job titles and their respective salary ranges.
- **Locations**: Stores office or company location details.
- **Job History**: Tracks the history of job changes for employees.

### Key Features:
- **Data Retrieval**: Select data based on various conditions such as salary, department, job title, and location.
- **Data Manipulation**: Add, update, and delete employee records with real-time changes.
- **Pattern Matching**: Search employee and location records using pattern matching with SQL `LIKE`.
- **Transactions**: Use SQL `ROLLBACK` and `COMMIT` to manage data consistency.
- **Backup and Restore**: Create backups of employee data and perform rollback or insert operations as needed.

## Tables and Structure

### `LOCATIONS`
Stores information about company locations (office, warehouse, production site).

### `DEPARTMENTS`
Contains details about company departments such as name, manager, and location.

### `JOBS`
Stores job roles and the respective salary ranges.

### `EMPLOYEES`
Contains employee details like name, job title, salary, department, manager, and commission percentage.

### `JOB_HISTORY`
Tracks the job history of employees, including past roles and departments.

## Operations and Queries

### Basic Queries
- Select all rows from `EMPLOYEES`, `DEPARTMENTS`, `LOCATIONS`, `JOBS`, etc.
- Retrieve records based on specific conditions like salary greater than 10,000, department name, and job title.

### Data Filtering
- Use `WHERE` clauses to filter employees by salary, department, job title, or location.
- Handle null values and missing data with `IS NULL`, `IS NOT NULL`.

### Sorting and Ordering
- Sort records by employee name, location postal code, and department name.
- Use `ORDER BY` with multiple columns for more complex sorting.

### Pattern Matching
- Use `LIKE` to find employees or locations with specific patterns in their names, job titles, or street addresses.

### Data Manipulation
- **Insert** new employee records into the `EMPLOYEES` table.
- **Update** records, e.g., fixing incorrect emails or setting commission percentages to 0.
- **Delete** records based on specific conditions.

### Backup and Rollback
- Create a backup of employee data with the `CREATE TABLE AS` operation.
- Perform `ROLLBACK` and `COMMIT` to ensure data integrity during operations.
- Use `TRUNCATE` to remove data from the backup table.

### Transactions
- Manage data consistency using `ROLLBACK` and `COMMIT` commands.
- Ensure that changes made within a session are either fully committed or rolled back if an error occurs.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/mini-sql-project.git
