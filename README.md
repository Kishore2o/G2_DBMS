## EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## AIM:
To create a student database and execute DDL queries using SQL.

## DDL (Data Definition Language)
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
## List of DDL commands:
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.
## Query:
## 1) Create a table student with the following fieds rollno,name,age,address,phoneno.
## SQL QUERY:
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```
## OUTPUT:
![image](https://github.com/Kishore2o/G2_DBMS/assets/118679883/49ee2d0c-02e9-4731-8d08-3a220a43b0ac)
## 2) Change the above student table by adding another attribute department
## SQL QUERY:
```
alter table student add department char(30);
```
## OUTPUT:
![image](https://github.com/Kishore2o/G2_DBMS/assets/118679883/4b5be6db-cda7-4e48-b654-ab64e0d45153)
## 3) Drop the student table
## SQL QUERY:
```
drop table student;
```
## OUTPUT:
![image](https://github.com/Kishore2o/G2_DBMS/assets/118679883/30aa9a22-1262-4327-9d19-e57a4e8ed7fd)
## 4) Delete the student table using truncate keyword
## SQL QUERY:
```
truncate table student;
```
## OUTPUT:
![image](https://github.com/Kishore2o/G2_DBMS/assets/118679883/e14e1514-c490-485a-9963-07e2afa9b531)
## 5) Rename the student table to mystudent
## SQL QUERY:
alter table student rename to mystudent;
## OUTPUT:
![image](https://github.com/Kishore2o/G2_DBMS/assets/118679883/08f54754-5007-4d70-a2a1-df95c3895267)
## RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
