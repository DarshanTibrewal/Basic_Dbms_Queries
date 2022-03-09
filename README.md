# Basic_Dbms_Queries
This a pratice repo , where i will save the codes which i ll be running while learning Database Management System and MySQL
CREATE TABLE emp
(
  ID INTEGER PRIMARY KEY,
  Name TEXT NOT NULL,
  Dept TEXT NOT NULL,
  Salary INTEGER NOT NULL
);


INSERT INTO emp VALUES (1, 'Ram', 'HR',10000);
INSERT INTO emp VALUES (2, 'Jhon', 'IT',15000);
INSERT INTO emp VALUES (3, 'Shyam', 'HR',10000);
INSERT INTO emp VALUES (4, 'Cena', 'MARKETING',15000);

SELECT * FROM emp WHERE Salary >= '11000';
