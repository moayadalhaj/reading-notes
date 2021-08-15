# Mongo and Mongoose

-----

## noSQL vs SQL

1. Fill in the chart below with five differences between SQL and NoSQL databases:

| SQL                                                                           | NoSQL                                             |
| :---------------------------------------------------------------------------- | :------------------------------------------------ |
| called as Relational Databases (RDBMS)                                        | called as non-relational or distributed database. |
| table based databases                                                         | document based                                    |
| predefined schema                                                             | dynamic schema for unstructured data.             |
| vertically scalable                                                           | horizontally scalable                             |
| uses SQL ( structured query language ) for defining and manipulating the data | focused on collection of documents.               |

### 1. What kind of data is a good fit for an SQL database?

- If the data is numeric, favor SMALLINT, INTEGER, BIGINT, DECIMAL, character, or data types. SQL databases are not best fit for hierarchical data storage.

### 2. Give a real world example

- SQL database examples: MySql, Oracle, Sqlite, Postgres and MS-SQL.

### 3. What kind of data is a good fit a NoSQL database?

- highly preferred for large data set (i.e for big data). hierarchical data is an example for this purpose.

### 4. Give a real world example

- NoSQL database examples: MongoDB, BigTable, Redis, RavenDb, Cassandra, Hbase, Neo4j and CouchDb

### 5. Which type of database is best for hierarchical data storage?

- NoSQL database.

### 6. Which type of database is best for scalability?

- SQL databases.

## sql vs nosql (Video)

### 1. What does SQL stand for?

- Structured Query Language.

### 2. What is a realational database?

- Is a type of database that stores and provides access to data points that are related to one another.

### 3. What type of structure does a relational database work with?

- B-TREE ,collection of tables, each having a unique name. A row in a table represents a relationship among a set of values. Thus a table represents a collection of relationships. There is a direct correspondence between the concept of a table and the mathematical concept of a relation.

### 4. What is a ‘schema’?

- Is a cognitive framework or concept that helps organize and interpret information, represents the logical configuration of all or part of a relational database.

### 5. What is NoSQL database?

- which stands for “not only SQL,” is an approach to database design that provides flexible schemas for the storage and retrieval of data beyond the traditional table structures found in relational database.

### 6. What is inside of a Mongo database?

- MongoDB stores data records as documents which are gathered together in collections. A database stores one or more collections of documents.

### 7. Which is more flexible - SQL or MongoDB? and why?

- MongoDB, some research has shown that the speed of MongoDB could be 100x faster than a relational database, and it has easy setup.

### 8. What is the disadvantage of a NoSQL database?

- Don't have the reliability functions which Relational Databases have (basically don't support ACID).

## Things I want to know more about

- How to work with databases and use them in my app.
