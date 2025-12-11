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
```
# EXPERIMENT 3 : DML COMMANDS
QUESTIONS

Question 1
Write a SQL statement to update the product_name as 'Grapefruit' whose product_id is 4 in the products table.

Question 2
Write a SQL query to reduce the reorder level by 30% where cost price is more than 50 and quantity in stock is less than 100 in the products table.

Question 3
Write a SQL query to Delete a Specific Surgery which was made on 28th Feb 2024.

Question 4
Write a SQL query to Delete customers from 'customer' table where 'GRADE' is not equal to 3.

Question 5
Write a query to fetch details of employees whose EmpLname ends with an alphabet ‘A’ and contains five alphabets.

Question 6
Write a SQL query to classify base in the Calculations table as 'Provided' if it is not NULL, otherwise 'Not Provided'.

Question 7
Write a SQL query to calculate the final price after applying both the discount and the tax. Return product_id, original_price, discount_percentage, tax_rate, and final_price.

Question 8
Create a report that shows the capitalized FirstName and capitalized LastName renamed as FirstName and Lastname respectively and EmployeeId from the employees table sorted by EmployeeId in descending order.

Question 9
Write a SQL statement to retrieve city(column name) of all customers from customers table without any repeats.

Question 10
Write a SQL statement to Double the salary for employees in department 20 who have a job_id ending with 'MAN'
```
