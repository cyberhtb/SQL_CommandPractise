
# SQL Command Instructions

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