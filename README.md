# Databases Playground Exercises - MySQL

Let's go to a playground tool to train SQL commands online:

https://extendsclass.com/mysql-online.html

MySQL Command Cheatsheet: https://devhints.io/mysql

In case you have MySQL installed on your machine:
- Login to MySQL: `mysql -u root -p`
- Create a database 'users_db'


## Create a table 'users'

Use the CREATE TABLE command to create a table "users".

The table users should have the following fields:

* ID Primary Key which increases automatically
* email with max 20 characters. Nulls not allowed
* password with max 40 characters
* firstname and lastname with max 20 characters. Null allowed
* isAdmin - a boolean field with a default value of 0
	* Research how to do a boolean field in MySQL + setting a default value for a column

* Check the structure of the table afterwards using DESCRIBE


## Create 3 user records

* Add an Admin user (= user record) to your users table with one SQL INSERT INTO statement
* Create now another TWO user records, this time NO admins, with another second SQL statement
    => provide the two records comma separated
* Check if it worked by selecting all records in the table using SELECT


## Perform CRUD on user records

Let's train some filtering, updating and deletion of user records

* Get all users who are not admin
* Update the password of user 3 to "NEW_PW" (select the user by email)
* Delete the user with the ID 3

