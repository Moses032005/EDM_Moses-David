# ‎Finals Lab Task 2. Transforming ER Model to Relational Tables
‎
Given the ER diagram representing student assignment submissions, convert it into MySQL
tables. Capture all entities and their attributes, and define the relationships between students,
submissions, and assignments. Identify the primary and foreign keys and ensure proper
representation of any dependent or weak entities.
 In converting the ER diagram, the following are the data types of the attributes:

‎![screenshot](/Finals%20Lab%20Task%202/Images/P2.A.png)

## STEP 1: Create a table named "Student Table" with the following fields:

- ‎Student Table:
  * username: String (VARCHAR), up to 50 characters.

## Here's my Query Statement with Table Structure 

‎![screenshot](/Finals%20Lab%20Task%202/Images/P2.1.png)


## STEP 2: Create a table named "Assignment Table" with the following fields:

- Assignment Table:
  * shortname: String (VARCHAR), up to 50 characters.
  * due date: Date, cannot be null.
  * url: String (VARCHAR), up to 255 characters, can be null


## Here's my Query Statement with Table Structure

‎![screenshot](/Finals%20Lab%20Task%202/Images/P2.2.png)

‎
## STEP 3: Create a table named "Submission Table" with the following fields:

- Submission Table:
 * username: String (VARCHAR), up to 50 characters.
 * shortname: String (VARCHAR), up to 50 characters.
 * version for integer, represents the version of the submission.
 * submit at Date, cannot be null
 * Data: Text.

# Note: Create the appropriate table relationship and enforce necessary REFERENTIAL INTEGRITY CONSTRAINTS

## Here's my Query Statement with Table Structure

‎![screenshot](/Finals%20Lab%20Task%202/Images/P2.3.png)

## Sample of my EER Diagram or Relational schema from phpMyAdmin or Workbench

‎![screenshot](/Finals%20Lab%20Task%202/Images/P2.EER.png)


[final lab task 2 sql.docx](https://github.com/user-attachments/files/19797300/final.lab.task.2.sql.docx)

