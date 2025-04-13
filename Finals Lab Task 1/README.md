# ‎Finals Lab Task 1. MySQL basics (Multi-Level Company)
The actions listed below require MySQL statements for implementation.
Make sure to finish them in the sequence indicated.
‎
## Task 1: Create a table named employees with the following fields:
- ‎employee_id: Unique integer, auto-increment, primary key.
- ‎employee_name: String (VARCHAR) with up to 255 characters, not null.
- ‎manager_id: Integer, foreign key referencing employee_id in the same table (employees).
  
‎![screenshot](/Finals%20Lab%20Task%201/Images/MySQL1.png)

## Task 2: Create a table named departments with the following fields:
‎- department_id: Unique integer, auto-increment, primary key.
- ‎department_name: String (VARCHAR) with up to 255 characters, not null.

‎![screenshot](/Finals%20Lab%20Task%201/Images/MySQL2.png)
‎
## Task 3: Create a table named employee_departments with the following fields:
- ‎employee_id: Integer, foreign key referencing employee_id in employees,
‎- ‎department_id: Integer, foreign key referencing department_id in departments.
‎- composite primary key (employee_id, department_id).

‎![screenshot](/Finals%20Lab%20Task%201/Images/MySQL3.png)
‎
## Task 4: Create a table named employee_projects with the following fields:
‎- employee_id: Integer, foreign key referencing employee_id in employees.
- ‎project name: String (VARCHAR) with up to 255 characters, not null.

‎![screenshot](/Finals%20Lab%20Task%201/Images/MySQL4.png)

‎## Task 5: Create a table named managers with the following fields:
- ‎manager_id: Unique integer, auto-increment, primary key.‎
‎- employee_id: Integer, foreign key referencing employee_id in employees.

‎![screenshot](/Finals%20Lab%20Task%201/Images/MySQL5.png)

## ER Diagram or Relational schema from phpMyAdmin or Workbench

‎![screenshot](/Finals%20Lab%20Task%201/Images/MySQLERD.png)

[Part1 MySQL Code.docx](https://github.com/user-attachments/files/19725738/Part1.MySQL.Code.docx)

