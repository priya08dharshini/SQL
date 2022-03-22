# SQL
concept and solved problems

1. What is a Database? How is it different from DBMS or RDBMS ?

The database is an organized collection of structured data to make it easily
accessible, manageable and updated. In simple words, you can say, a database in a
place where the data is stored. The best analogy is the library. The library contains a
huge collection of books of different genres, here the library is a database and books
are the data.

Database Management System (DBMS) is a software that is used to define, create and
maintain a database and provides controlled access to the data,or basically it’s a
software that interacts with the database. and RDBMS can be considered as a specific
form of the DBMS , in which data is divided into different tables and these tables are
further being related to each other by some key columns.

2. What is SQL?

SQL stands for Structured Query Language. SQL is used to communicate with a
database. According to ANSI (American National Standards Institute), it is the standard
language for relational database management systems. SQL statements are used to
perform tasks such as update data on a database, or retrieve data from a database.

3. Different types of Statement in SQL?

There are five types of SQL commands: DDL, DML, DCL, TCL, and DQL.

1. Data Definition Language (DDL)

DDL changes the structure of the table like creating a table, deleting a table, altering a
table, so whenever you are actually changing the structure of a table by a particular
command, that will come under DDL.
All the commands of DDL are auto-committed, which means it permanently saves all
the changes in the database.
Here are some commands that come under DDL:
1 CREATE
2 ALTER
3 DROP
4 TRUNCATE

2. Data Manipulation Language (DML)

o DML commands are used to modify the database. It is responsible for all forms of
changes in the database. So whenever you are making any kind of change to a
database without modifying the original structure of it.
o The command of DML is not auto-committed, which means it can't permanently
save all the changes in the database. They can be rolled back.
Here are some commands that come under DML:
 INSERT
 UPDATE
 DELETE

3- Data Control Language(DCL)

DCL commands are used to grant and take back authority from any database user to
view or edit the database or a particular instance of it
Here are some commands that come under DCL:
 Grant
 Revoke
 
4- Transaction Control Language(TCL)

TCL commands can only be used with DML commands like INSERT, DELETE and
UPDATE only.
These operations are automatically committed in the database that's why they cannot
be used while creating tables or dropping them.
Here are some commands that come under TCL:
 COMMIT
 ROLLBACK
 SAVEPOINT
 
5- Data Query Language(DQL)

DQL is used to fetch the data from the database.
It uses only one command:
 SELECT


3. strong in this concept in w3school (link: https://www.w3schools.com/sql/)
