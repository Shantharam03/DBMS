# DBMS
#Experiment 2: DDL Commands
```
QUESTIONS:
Question 1
Create a new table named item with the following specifications and constraints:

item_id as TEXT and as primary key.
item_desc as TEXT.
rate as INTEGER.
icom_id as TEXT with a length of 4.
icom_id is a foreign key referencing com_id in the company table.
The foreign key should cascade updates and deletes.
item_desc and rate should not accept NULL.

Question 2
Insert all books from Out_of_print_books into Books Table attributes are ISBN, Title, Author, Publisher, YearPublished

Question 3
Write a SQL query to Add a new column Country as text in the Student_details table. Sample table: Student_details

Question 4
Create a table named Locations with the following columns:

LocationID as INTEGER
LocationName as TEXT
Address as TEXT

Question 5 
Insert a book with ISBN 978-1234567890, Title Data Science Essentials, Author Jane Doe, Publisher TechBooks, and Year 2024 into the Books table.

Question 6
In the Student_details table, insert a student record where some fields are NULL, another record where all fields are filled without any NULL values, and a third record where some fields are filled, and others are left as NULL.

Question 7
Create a table named Bonuses with the following constraints:

BonusID as INTEGER should be the primary key.
EmployeeID as INTEGER should be a foreign key referencing Employees(EmployeeID).
BonusAmount as REAL should be greater than 0.
BonusDate as DATE.
Reason as TEXT should not be NULL.

Question 8
create a table named jobs including columns job_id, job_title, min_salary and max_salary, and make sure that, the default value for job_title is blank and min_salary is 8000 and max_salary is NULL will be entered automatically at the time of insertion if no value assigned for the specified columns.

Question 9
Write an SQL Query to add the attributes designation, net_salary, and dob to the Companies table with the following data types:

designation as VARCHAR(50)
net_salary as NUMBER
dob as DATE

Question 10
Create a table named Invoices with the following constraints:


InvoiceID as INTEGER should be the primary key.
InvoiceDate as DATE.
Amount as REAL should be greater than 0.
DueDate as DATE should be greater than the InvoiceDate.
OrderID as INTEGER should be a foreign key referencing Orders(OrderID).
```
