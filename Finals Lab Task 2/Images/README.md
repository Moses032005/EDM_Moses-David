# ‎Finals Lab Task 2. Transforming ER Model to Relational Tables
‎
Given the ER diagram representing student assignment submissions, convert it into MySQL
tables. Capture all entities and their attributes, and define the relationships between students,
submissions, and assignments. Identify the primary and foreign keys and ensure proper
representation of any dependent or weak entities.
 In converting the ER diagram, the following are the data types of the attributes:

![P2 A](https://github.com/user-attachments/assets/bd3d1d83-8cd6-461f-8c02-12505c90e1cc)


## STEP 1: Create a table named "Student Table" with the following fields:

- ‎student table:
  * username: String (VARCHAR), up to 50 characters.

## Here's my Query Statement with Table Structure 

![P2 1 - Copy](https://github.com/user-attachments/assets/698492d3-7424-404f-b338-728073a02c46)


## STEP 2: Create a table named "Assignment Table" with the following fields:

- assignment table:
  * shortname: String (VARCHAR), up to 50 characters.
  * due date: Date, cannot be null.
  * url: String (VARCHAR), up to 255 characters, can be null


## Here's my Query Statement with Table Structure

![P2 2](https://github.com/user-attachments/assets/23d07301-18f8-44e0-a42e-208b11fc0c0a)

‎
## STEP 3: Create a table named "Submission Table" with the following fields:

- submmission table:
* username: String (VARCHAR), up to 50 characters.
* shortname: String (VARCHAR), up to 50 characters.
* version for integer, represents the version of the submission.
* submit at Date, cannot be null
* Data: Text.

# Note: Create the appropriate table relationship and enforce necessary REFERENTIAL INTEGRITY CONSTRAINTS

## Here's my Query Statement with Table Structure

![P2 3](https://github.com/user-attachments/assets/4ac0156e-e4d1-49d6-82f8-8680f63689e0)

## Sample of my EER Diagram or Relational schema from phpMyAdmin or Workbench

![Final Lab Task2](https://github.com/user-attachments/assets/f61a32c3-25bb-49cb-a622-5ac8ccf7f04f)



[final lab task 2 sql.docx](https://github.com/user-attachments/files/19797300/final.lab.task.2.sql.docx)
