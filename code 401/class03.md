# Readings: SQL database, ORM, Sequelize

**1. What's the difference between SQL  and NoSQL?**
- 
| SQL |	NoSQL|
|---------|-----------|
|RELATIONAL DATABASE MANAGEMENT SYSTEM (RDBMS)|	Non-relational or distributed database system.|
|
|These databases have fixed or static or predefined schema	|They have dynamic schema|
|
|These databases are not suited for hierarchical data storage.|These databases are best suited for hierarchical data storage.|
|
|These databases are best suited for complex queries	|These databases are not so good for complex queries|
|
|Vertically Scalable	|Horizontally scalable|
|
|Follows ACID property	|Follows CAP(consistency, availability, partition tolerance)|
|
|Examples: MySQL, PostgreSQL, Oracle, MS-SQL Server etc	|Examples: MongoDB, GraphQL, HBase, Neo4j, Cassandra etc|

<br>

**2. What is Sequelize  and how to use it with Node js?**
-  is an open-source Node.js module that enables JavaScript developers to work with relational databases more easily, including but limited to MySQL, Postgres.
-
**3. What is an ORM, how does it work, and how should I use one?**
- is simply an Object Relational Mapper that helps in data manipulation and querying by the use of objects from the database. Using an ORM optimizes SQL queries making them easy to reuse and maintain.

### The types of Object Relational Mappers with Node.js support are:

1. Sequelize which has support for PostgreSQL, MySQL, MariaDB, SQLite, and Microsoft SQL Server databases.

2. Caminte supports a large number of databases such as MySQL Sqlite3, Riak, Postgres, CouchDB, MongoDB, Redis.

3. Node-ORM has support for MySQL, SQLite, and PostgreSQL.

#  Vocabulary

**SQL :** ( Structured Query Language ) is a standardized programming language that is used to manage relational databases and perform various operations on the data in them

**NoSQL :** NoSQL databases (aka "not only SQL") are non-tabular databases and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model

**Database schema :** A database schema defines how data is organized within a relational database; this is inclusive of logical constraints such as, table names, fields, data types, and the relationships between these entities

**WRRC :**