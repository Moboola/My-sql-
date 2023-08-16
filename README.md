# My-sql-
This repository serves the purpose of crafting a database, formulating SQL queries and carrying out their execution, debugging SQL queries, as well as crafting Entity-Relationship Diagrams (EER Diagrams). Furthermore, it entails comprehending data relationships and discerning primary and foreign keys within the schema.
You can find the link here:-

USE store;
1.This query selects the database schema or database name to be used for subsequent queries. In       this case, the "store" schema or database will be used.
2 SELECT * FROM customers;
This query retrieves all the rows from the "customers" table and displays all the columns for each row.
3. SELECT * FROM customers ORDER BY first_name;
This query retrieves all the rows from the "customers" table and sorts them in ascending order based on the "first_name" column.
4. SELECT birth_date FROM customers WHERE birth_date <= '1990-01-01';
This query selects the "birth_date" column from the "customers" table and retrieves all the rows where the birth date is earlier than or equal to January 1, 1990.
5. SELECT * FROM customers WHERE first_name like 'M%' and last_name like 'A%';
This query retrieves all the rows from the "customers" table where the "first_name" starts with the letter 'M' and the "last_name" starts with the letter 'A'.
6.SELECT last_name, first_name, points FROM customers;
This query selects the "last_name," "first_name," and "points" columns from the "customers" table and displays them in the output.
7. SELECT MIN(points), MAX(points) FROM customers;
This query calculates the minimum and maximum values of the "points" column in the "customers" table and displays them in the output.
8. SELECT * FROM customers ORDER BY points DESC LIMIT 5;
This query retrieves all the rows from the "customers" table, sorts them in descending order based on the "points" column, and limits the output to the first five rows with the highest points.
9. SELECT * FROM customers ORDER BY last_name;
This query retrieves all the rows from the "customers" table and sorts them in ascending order based on the "last_name" column.

![image](https://github.com/Moboola/My-sql-/assets/142215138/eab2c68d-2988-4c72-b36f-4a52b531e2a7)
![image](https://github.com/Moboola/My-sql-/assets/142215138/cad7205b-b298-4923-a779-3f1be36a784d)
                IDENTIFYING PRIMARY KEY AND FOREIGN KEY
primary key in country table: Product id INT, Customer Id INT
primary key in city table: Customer Id INT
primary key in countrylanggage table: Order Id INT
primary key in countrylanggage table: Shipper Id INT SMALL INT

Foreign key in city table : Order Id INT
 
Foreign key in countrylanggage table:  Customer Id INT (11)
