# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE: 4/8/23
## AIM:
To create a student database and execute DDL queries using SQL.
## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```
### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/G2_DBMS/assets/122046208/c89e8c63-52b3-48a3-b3b0-471631db6d84)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);

```
### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/G2_DBMS/assets/122046208/725692c7-eef6-40ef-8b47-9731b3ca441a)

### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;

```
### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/G2_DBMS/assets/122046208/26823ba6-864a-4f28-9df3-9134703a899e)

### 4) Delete the student table using truncate keyword
### SQL QUERY: 
```
truncate table student;

```
### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/G2_DBMS/assets/122046208/7cd88ed8-dffc-4c33-98df-b986f4d2edd4)

### 5) Rename the student table to mystudent
### SQL QUERY: 
```
alter table student rename to mystudent;

```
### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/G2_DBMS/assets/122046208/ce3d012e-6ef1-414f-a81f-b6d744d5acfb)

### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
