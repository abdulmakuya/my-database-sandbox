# Resources
Databases has 
1.DML.  
2.DDL.  
3.DQL.  

W3 Schools
SQL Data Modeler
Workbench
QueryBrowser
Top mysql database tools
MongoDB

```sql
select * from student where debt between "100,000"
and "750,000";
```

# Initialization
```sql
cd C:\xampp\mysql\bin
prompt>mysql -u root -h localhost -p
show databases;
use [database_name];
show tables;
DESCRIBE dbname.tablename;
CTRL+Break
```
```sql
CREATE db.tablename(
col1 INT AUTO_INCREMENT NOT NULL PRIMARY KEY,
col2 VARCHAR(20) NOT NULL,
col3 VARCHAR(20) NOT NULL);
```

```sql
INSERT INTO [tablename]
(firstcolumn,seccolumn,thirdcolumn)
VALUES
('attributeValue','attributeValue','attributeValue');
```

```sql
ALTER TABLE name ADD column_name TYPE     - after/before

ALTER TABLE name DROP column_name 

ALTER TABLE name CHANGE column_name new_name new type
```
```sql
ALTER TABLE employee
ADD CONSTRAINT employee_airline_fk FOREIGN KEY(id) 
REFERENCES airline (id);



SELECT employee.name,employee.age
FROM employee
INNER JOIN airline
ON employee.airline_id=airline.airline_id
WHERE airline.adress='dar';

//this will list all employees by name and age whose airlines are 
//based in dar
```

```sql
Data Definition statement
ALTER 
RENAME
CREATE
DROP

DATA MANIPULATION Statements
INSERT
UPDATE
DELETE
TRUNCATE

```
