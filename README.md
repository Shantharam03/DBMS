# DBMS
```
#Experiment 2: DDL Commands
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
```
# EXPERIMENT 3 : DML COMMANDS
QUESTIONS:
question 1
How many appointments are scheduled for each patient?

Question 2
-- What is the average duration of insurance coverage for patients covered by each insurance company?

Question 3
-- How many prescriptions were written in each frequency category (e.g., once daily, twice daily)?

Question 4
-- Write a SQL query to find the average salary of all employees?

Question 5
-- Write a SQL query that counts the number of unique salespeople. Return number of salespeople.

Question 6
-- Write a SQL query to return the total number of rows in the 'customer' table where the city is not Noida.

Question 7
-- Write a SQL query to find What is the age difference between the youngest and oldest employee in the company.

Question 8
--Write the SQL query that accomplishes the grouping of data by joining date (jdate), calculates the minimum work hours for each date, and excludes dates where the minimum work hour is not less than 10.

Question 9
-- Write the SQL query that accomplishes the grouping of data by joining date (jdate), calculates the total work hours for each date, and excludes dates where the total work hour sum is not greater than 40.

Question 10
-- Write the SQL query that achieves the grouping of data by age, calculates the minimum income for each age group, and includes only those age groups where the minimum income is less than 400,000.
```
```
#EXPERIMENT 5: SUBQURIES VIEWS:
Question 1
Write a SQL query that retrieve all the columns from the table "Grades", where the grade is equal to the maximum grade achieved in each subject. Sample table: GRADES (attributes: student_id, student_name, subject, grade)

Question 2
Write a SQL query to Identify customers whose city is different from the city of the customer with the highest ID

SAMPLE TABLE: customer

name             type
---------------  ---------------
id               INTEGER
name             TEXT
city             TEXT
email            TEXT
phone            INTEGER

Question 3
Write a SQL query to retrieve all columns from the CUSTOMERS table for customers whose salary is LESS than $2500.

Question 4
From the following tables write a SQL query to count the number of customers with grades above the average in New York City. Return grade and count.

customer table

name         type
-----------  ----------
customer_id  int
cust_name    text
city         text
grade        int
salesman_id  int

Question 5
Write a SQL query to retrieve all columns from the CUSTOMERS table for customers whose Address as Delhi

Question 6
From the following tables write a SQL query to find the order values greater than the average order value of 10th October 2012. Return ord_no, purch_amt, ord_date, customer_id, salesman_id.

Note: date should be yyyy-mm-dd format

ORDERS TABLE

name            type
----------     ----------
ord_no          int
purch_amt    real
ord_date       text
customer_id  int
salesman_id  int

Question 7
From the following tables write a SQL query to find all orders generated by New York-based salespeople. Return ord_no, purch_amt, ord_date, customer_id, salesman_id.

salesman table

name             type
---------------  ---------------
salesman_id      numeric(5)
name                 varchar(30)
city                    varchar(15)
commission       decimal(5,2)
orders table

name             type
---------------  --------
order_no         int
purch_amt        real
order_date       text
customer_id      int
salesman_id      int

Question 8
From the following tables, write a SQL query to find those salespeople who earned the maximum commission. Return ord_no, purch_amt, ord_date, and salesman_id.

salesman table

name             type
---------------  ---------------
salesman_id      numeric(5)
name                 varchar(30)
city                    varchar(15)
commission       decimal(5,2)
orders table

name             type
---------------  --------
order_no         int
purch_amt        real
order_date       text
customer_id      int
salesman_id      int

Question 9
From the following tables, write a SQL query to find all the orders generated in New York city. Return ord_no, purch_amt, ord_date, customer_id and salesman_id.

SALESMAN TABLE

name               type
-----------        ----------
salesman_id  numeric(5)
name             varchar(30)
city                 varchar(15)
commission   decimal(5,2)
ORDERS TABLE

name            type
----------      ----------
ord_no          int
purch_amt    real
ord_date       text
customer_id  int
salesman_id  int

Question 10
Write a SQL query that retrieves the all the columns from the Table Grades, where the grade is equal to the minimum grade achieved in each subject.

Sample table: GRADES (attributes: student_id, student_name, subject, grade)
```
