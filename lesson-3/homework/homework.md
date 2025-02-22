# Lesson 3: Importing and Exporting Data

Here are 30 homework tasks for Lesson 3, categorized into easy, medium, and hard levels. These tasks cover:

✅ Importing Data (BULK INSERT, Excel, Text, XML, JSON)
✅ Exporting Data (Excel, Text, XML, JSON)
✅ Comments, Identity column, NULL/NOT NULL values
✅ Unique Key, Primary Key, Foreign Key, Check Constraint
✅ Differences between UNIQUE KEY and PRIMARY KEY

________________________________________

## 🟢 Easy-Level Tasks (10)
1. Define and explain the purpose of BULK INSERT in SQL Server.
2. List four file formats that can be imported into SQL Server.
3. Create a table Products with columns: ProductID (INT, PRIMARY KEY), ProductName (VARCHAR(50)), Price (DECIMAL(10,2)).
4. Insert three records into the Products table using INSERT INTO.
5. Explain the difference between NULL and NOT NULL with examples.
6. Add a UNIQUE constraint to the ProductName column in the Products table.
7. Write a comment in a SQL query explaining its purpose.
8. Create a table Categories with a CategoryID as PRIMARY KEY and a CategoryName as UNIQUE.
9. Export data from the Products table to a CSV file using SSMS.
10. Explain the purpose of the IDENTITY column in SQL Server.

________________________________________

## 🟠 Medium-Level Tasks (10)
11. Use BULK INSERT to import data from a text file into the Products table.
12. Import data from an Excel file into a table called Sales using SSMS Import Wizard.
13. Write a query that exports the Products table data into an XML format using FOR XML.
14. Create a FOREIGN KEY in the Products table that references the Categories table.
15. Explain the differences between PRIMARY KEY and UNIQUE KEY with examples.
16. Add a CHECK constraint to the Products table ensuring Price > 0.
17. Write a query to export data from SQL Server to a JSON file.
18. Modify the Products table to add a column Stock (INT, NOT NULL).
19. Use the ISNULL function to replace NULL values in a column with a default value.
20. Describe the purpose and usage of FOREIGN KEY constraints in SQL Server.

________________________________________

## 🔴 Hard-Level Tasks (10)
21. Write a script to create a Customers table with a CHECK constraint ensuring Age >= 18.
22. Import data from a JSON file into a table called Orders using OPENROWSET.
23. Create a table with an IDENTITY column starting at 100 and incrementing by 10.
24. Write a query that exports multiple tables into separate Excel sheets using SSMS.
25. Write a query to create a composite PRIMARY KEY in a new table OrderDetails.
26. Explain with examples the use of COALESCE and ISNULL functions for handling NULL values.
27. Use the MERGE statement to import data from a text file into Products, updating existing records and inserting new ones.
28. Create a table Employees with both PRIMARY KEY on EmpID and UNIQUE KEY on Email.
29. Write a query to create a FOREIGN KEY with ON DELETE CASCADE and ON UPDATE CASCADE options.
