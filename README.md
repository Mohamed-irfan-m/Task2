# Task2
Employee Management SQL Practice
This project demonstrates practical usage of SQL INSERT, UPDATE, DELETE, ALTER, and DROP statements to clean and manage employee data in a sample database.

* Project Structure
task2.sql – SQL script with data insertion, updates, deletions, and schema modifications

README.md – Overview of SQL operations and project steps

* Tools Used
MySQL Workbench

SQL (MySQL dialect)

(Optional) Sample dataset inspired by Kaggle

* Table Overview
The schema includes a single table:

Employe_table – Stores employee details including name, department, salary, manager relationships, and contact information.

* Operations Performed
* INSERT
Inserted multiple employee records into the table.

Included some rows with missing values to simulate real-world data inconsistencies.

* UPDATE
Updated missing Salary values to use the default of 30000.

Corrected missing Department values for specific employees based on known names.

* DELETE
Removed employees with missing email addresses using:


* ALTER / DROP
Removed the unnecessary HireDate column using:

* Relationships
The ManagerID column establishes a self-referencing relationship, indicating that an employee can report to another employee.

A foreign key constraint can be added later to enforce this hierarchy.
