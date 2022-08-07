# Reading

1. Five differences between SQL and NoSQL databases:



|   Num | SQL | NoSQL |
|-----------|-----------|---|
| 01 | Are primarily called as Relational Databases (RDBMS). | Are primarily called as non-relational or distributed database. |
| 02 | Are table based databases. | Are document based, key-value pairs, graph databases or wide-column stores. |
| 03 | Vertically scalable | Horizontally scalable |
| 04 |  have predefined schema for unstructured data | have dynamic schema for unstructured data |
| 05 | Are scaled by increasing the horse-power of the hardware | Are scaled by increasing the databases servers in the pool of resources to reduce the load | 

<br>

2. What kind of data is a good fit for an SQL database?
-  SQL databases are good fit for the complex query intensive environment.

3. Give a real world example.
-  MySql, Oracle, Sqlite, Postgres and MS-SQL

4. What kind of data is a good fit a NoSQL database?
-  NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data. NoSQL database are highly preferred for large data set (i.e for big data).

5. Give a real world example.
-  MongoDB, BigTable, Redis, RavenDb, Cassandra, Hbase, Neo4j and CouchDb

6. Which type of database is best for hierarchical data storage?
- NoSQL database.
7. Which type of database is best for scalability?
-  SQL databases are vertically scalable.
- NoSQL databases are horizontally scalable.


_______________________________________________
 
# Videos

1. What does SQL stand for?
- Structured Query Language

2. What is a relational database?
- a type of database that stores and provides access to data points that are related to one another. 

3. What type of structure does a relational database work with?
- Data is represented in tables using the relational model,
4. What is a ‘schema’?
-  tells us about the structural view of the database.
5. What is a NoSQL database?
-  NoSQL stands for “not only SQL. This means a NoSQL JSON database can store and retrieve data using literally “no SQL.” Or you can combine the flexibility of JSON with the power of SQL for the best of both worlds.
6. How does it work?
- store data in documents rather than relational tables.

7. What is inside of a Mongo database?
- one or more collections of documents.

8. Which is more flexible - SQL or MongoDB? and why.

- MongoDB is more flexible and ensures high and diverse data availability, a SQL Database operates with the ACID (Atomicity, Consistency, Isolation, and Durability) properties and ensures greater reliability of transactions. 

9. What is the disadvantage of a NoSQL database?
- (i) Lack of Standardization:

There is no standard that defines rules and roles of NoSQL databases. The design and query languages of NoSQL databases vary widely between different NoSQL products – much more widely than they do among traditional SQL databases.

 

(ii) Backup of Database:

Backups are a drawback in NoSQL databases. Though some NoSQL databases like MongoDB provide some tools for backup, these tools are not mature enough to ensure proper complete data backup solution.

 

(iii) Consistency:

NoSQL puts a scalability and performance first but when it comes to a consistency of the data NoSQL doesn’t take much consideration so it makes it little insecure as compared to the relational database e.g., in NoSQL databases if you enter same set of data again, it will take it without issuing any error whereas relational databases ensure that no duplicate rows get entry in databases.

