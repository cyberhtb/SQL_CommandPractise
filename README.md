
# SQL Command Instructions

- Created a database with table inside

```sql
-- Creating a database named "users"
CREATE DATABASE users;

-- use database "users"
USE users;

-- after getting inside database "users" created a table "logins"
CREATE TABLE logins(
	-- INT is data type for (id) field
	id INT, 

	-- VARCHAR(100) is a variable-length charac string with a maximum length of 100 characters.
    username VARCHAR(100),
    password VARCHAR(100),

    -- DATETIME use to storing data and time values. 
    date_of_joining DATETIME
);
```

- Command to perform some activity in table

```sql

-- it shows all table containing in database
SHOW TABLES;

-- describe an specific table contents

DESCRIBE egtablename;

```

- Command to alter table column and it's properties

```sql

-- "INT" is column type, "NOT NULL" make sure column never remain NULL & "AUTO_INCREMENT" do as it sound increase value automatically 

ALTER TABLE table_name
MODIFY COLUMN column_name INT NOT NULL AUTO_INCREMENT,
ADD PRIMARY KEY (column_name);
```
