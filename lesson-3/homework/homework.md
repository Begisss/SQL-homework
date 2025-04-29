# Lesson 3: Importing and Exporting Data

Here are 30 homework tasks for Lesson 3, categorized into easy, medium, and hard levels. These tasks cover:

✅ Importing Data (BULK INSERT, Excel, Text)
✅ Exporting Data (Excel, Text)
✅ Comments, Identity column, NULL/NOT NULL values
✅ Unique Key, Primary Key, Foreign Key, Check Constraint
✅ Differences between UNIQUE KEY and PRIMARY KEY

> **Notes before doing the tasks:**
> - Tasks should be solved using **SQL Server**.
> - Case insensitivity applies.
> - Alias names do not affect the score.
> - Scoring is based on the **correct output**.
> - One correct solution is sufficient.

______________________________________

## 🟢 Easy-Level Tasks (10)
1. Define and explain the purpose of BULK INSERT in SQL Server.
2. List four file formats that can be imported into SQL Server.
3. Create a table Products with columns: ProductID (INT, PRIMARY KEY), ProductName (VARCHAR(50)), Price (DECIMAL(10,2)).
4. Insert three records into the Products table using INSERT INTO.
5. Explain the difference between NULL and NOT NULL.
6. Add a UNIQUE constraint to the ProductName column in the Products table.
7. Write a comment in a SQL query explaining its purpose.
8. Create a table Categories with a CategoryID as PRIMARY KEY and a CategoryName as UNIQUE.
9. Explain the purpose of the IDENTITY column in SQL Server.

________________________________________

## 🟠 Medium-Level Tasks (10)
10. Use BULK INSERT to import data from a text file into the Products table.
11. Create a FOREIGN KEY in the Products table that references the Categories table.
12. Explain the differences between PRIMARY KEY and UNIQUE KEY.
13. Add a CHECK constraint to the Products table ensuring Price > 0.
14. Modify the Products table to add a column Stock (INT, NOT NULL).
15. Use the ISNULL function to replace NULL values in Price column with a 0.
16. Describe the purpose and usage of FOREIGN KEY constraints in SQL Server.

________________________________________

## 🔴 Hard-Level Tasks (10)
17. Write a script to create a Customers table with a CHECK constraint ensuring Age >= 18.
18. Create a table with an IDENTITY column starting at 100 and incrementing by 10.
19. Write a query to create a composite PRIMARY KEY in a new table OrderDetails.
20. Explain the use of COALESCE and ISNULL functions for handling NULL values.
21. Create a table Employees with both PRIMARY KEY on EmpID and UNIQUE KEY on Email.
22. Write a query to create a FOREIGN KEY with ON DELETE CASCADE and ON UPDATE CASCADE options.
