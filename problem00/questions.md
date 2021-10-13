## What is a DBMS?
### A database is usually controlled by a database management system (DBMS). Together, the data and the DBMS, along with the applications that are associated with them, are referred to as a database system. 

## What is RDBMS? (Characteristics and Properties)
### The software used to store, manage, query, and retrieve data stored in a relational database is called a relational database management system (RDBMS). The RDBMS provides an interface between users and applications and the database, as well as administrative functions for managing data storage, access, and performance.

## What is SQL? (Characteristics and Properties)
###  SQL stands for Structured Query Language which is a language used by databases. This language allows to handle the information using tables and shows a language to query these tables and other objects related (views, functions, procedures, etc.).
### -> SQL is easy to learn.
### -> SQL is used to access data from relational database management systems.
### -> SQL can execute queries against the database.
### -> SQL is used to describe the data.
### -> SQL is used to define the data in the database and manipulate it when needed.
### -> SQL is used to create and drop the database and table.
### -> SQL is used to create a view, stored procedure, function in a database.
### -> SQL allows users to set permissions on tables, procedures, and views.


## What is NoSQL? (Characteristics and Properties)
### NoSQL databases deemphasize the principles of ACID (atomicity, consistency, isolation, and durability). In addition, the process of normalization is not mandatory in NoSQL. Because of the size and speed of modern data, you shoud de-normalize NoSQL databases.

### They have higher scalability.
### They use distributed computing.
### They are cost effective.
### They support flexible schema.
### They can process both unstructured and semi-structured data.
### There are no complex relationships, such as the ones between tables in an RDBMS.


## List different RDBMS Software (At least 5)
### MS SQL.
### Oracle Database.
### MySQL.
### IBM Db2.
### Amazon Relational Database Service (RDS)

## List different NoSQL Software (At least 5)
### MongoDB. MongoDB is the most widely used document-based database. ...
### Cassandra. Cassandra is an open-source, distributed database system that was initially built by ### Facebook (and motivated by Google's Big Table). ...
### ElasticSearch. 
### Amazon DynamoDB. ...
### HBase.



## Difference between Oracle and MYSQL?
### MySQL provides a GPL software license, while Oracle doesn’t. 
### Oracle is compatible wiht Linux, UNIX, Windows, Mac OS X and z/OS. MySQL is compatible with all of those plus Symbian, BSD, and AmigaOS. 
### MySQL supports full-text and hash indexing only. Oracle uses more indexes than just these, including Bitmap, function-based, Partitioned, and so forth.
### Oracle supports distributed databases while MySQL doesn’t
### Oracle is better for enterprise deployments, while MySQL is suited for small to medium scale.
### MySQL is free, while Oracle requires a licensing fee

## Difference between Oracle and MongoDB?
### Oracle
### It was developed by Oracle Corporation in 1980.
### It is written in C and C++.
### It is a commercial software.
### Server operating systems for Oracle are Solaris, Linux, OS X, Windows.
### It uses Horizontal partitioning method for storing different data on different nodes.
### Referential integrity is used in Oracle.
### Referential integrity is used in Oracle.

### MongoDB
### It was developed by MongoDB Inc. in 2009.
### It is written in C++, Go, JavaScript, Python languages.
### It is an open-source software.
### Server operating systems for MongoDB are Solaris, Linux, OS X, Windows, AIX, HP-UX.
### It uses Sharding partitioning method for storing different data on different nodes.
### No concept of referential integrity and no Foreign keys.

## What are current version of Oracle and MySQL and MongoDB?
### Oracle Version 19C
### MongoDB 5.0
### MySQL 8.0 version

## What are the uses of RDBMS?
### 1. Data Structure:
### Data stored in a table format helps database users easy to understand, provides easy data access and simple origination of data. Similar kind of data cane be stored under a table name, with readable names.

### 2. Multi-User Access:
### RDBMSs allow multiple database users to access a database simultaneously. Built-in locking and transactions management functionality allow users to access data as it is being changed, prevents collisions between two users updating the data, and keeps users from accessing partially updated records.

### 3. Privileges:
### Authorization and privilege control features in an RDBMS allow the database administrator to restrict access to authorized users, and grant privileges to individual users based on the types of database tasks they need to perform. Authorization can be defined based on the remote client IP address in combination with user authorization, restricting access to specific external computer systems.

### 4. Network Access:
### RDBMSs provide access to the database through a server daemon, a specialized software program that listens for requests on a network, and allows database clients to connect to and use the database. Users do not need to be able to log in to the physical computer system to use the database, providing convenience for the users and a layer of security for the database. Network access allows developers to build desktop tools and Web applications to interact with databases.

## What is PLSQL and how is it different from MongoDB
### PL/SQL is a block structured language that enables developers to combine the power of SQL with procedural statements.All the statements of a block are passed to oracle engine all at once which increases processing speed and decreases the traffic.
