# MySQL

## Discription
MySQL is pronounced either "My S-Q-L" or "My Sequel",is an open source relational database management system.It is based on the structure query language(SQL),which is used for adding,removing, and modifying information in the database

### Prerequisites
1 To start any language you should first know the use of that language.MySQL is used for creating and managing database.

2 Install MySQL from browser

#### Installation
1 Download MySQL from [MySQL](https://dev.mysql.com/downloads/)

2 extract the files

3 move the data folder(optional)

4 create a configuration file

5 test your installation

6 change the root password

<!-- Images -->
![MySQL Logo](https://www.google.com/imgres?imgurl=https%3A%2F%2Fcdn.worldvectorlogo.com%2Flogos%2Fmysql.svg&imgrefurl=https%3A%2F%2Fworldvectorlogo.com%2Flogo%2Fmysql&tbnid=Bgugh_pvo8X-JM&vet=12ahUKEwihsqjB0LvtAhWOn0sFHV07AbYQMygAegUIARDKAQ..i&docid=tIz-HXUbbG9S5M&w=2500&h=1733&q=mysql%20logo&ved=2ahUKEwihsqjB0LvtAhWOn0sFHV07AbYQMygAegUIARDKAQ)

##### Usage 
MySQL is a relational database management system based on SQL-Structured Query Language.The application is used for a wide range of purposes,including data warehousing,e-commerce,and logging applications.The most common use for MySQL is for the purpose of a web database.


###### MySQL COMMANDS
|Description|Command|
|-----------|-------|
|To login|[mysql]/bin/mysql -h hostname -u root -p|
|create a database on the sql server|create database [database name];|
|list all database on the sql server|show database;|
|switch to database|use [db name];
|to see all the tables in the db|show tables;|
|to delete a db|drop db [db name];|
|to delete a table|drop atble [table name];|
|show all data in a table|select*from [table name];|

1 DDL Command

     *CREATE

     *ALTER

     *DROP

     *TRUNCATE

     *COMMENT

     *RENAME

2 DML Command

     *SELECT

     *INSERT

     *UPDATE

     *DELETE 

     *MERGE

     *CALL

     *EXPLAIN PLAN

     *LOCK TABLE

3 DCL Command 

    *GRANT

    *REVOKE

4 TCL Command

    *COMMIT

    *ROLLBACK

    *SAVEPOINT

    *SET TRANSACTION


CREATE TABLE IF NOT EXISTS `comments`

 (`com_id` int(11) NOT NULL AUTO_INCREMENT,

 `com_name` varchar(500) CHARACTER SET utf8_bin NOT NULL,
 
 `com_content` text CHARACTER SET utf8-bin NOT NULL,
 
 `com_website` varchar(500) CHARACTER SET utf8_bin NOT NULL,)


 ####### Credits

 contributer to MySQL

  [MySQL](HTTPS;//mysql.com/.)

  


