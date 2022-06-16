# Read 04

## Data Modeling

### NoSQL vs SQL<sup>1</sup>

#### 1. What type of database is the best fit for the complex query intensive environment?

SQL

#### 2. What type of database is the best fit for hierarchical data storage?

NoSQL

#### 3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

To scale SQL, you need to add more processing power - RAM, SSD, CPU
To scale NoSQL, you need to add more servers to the database - more interconnected computers

### SQL modeling techniques<sup>2</sup>

#### 1. Among data tables, what is a one-to-many relationship and how do we “relate” them?

A single entry in one table can be related to many others. The single entry is the common factor of all the other entries it relates to.

#### 2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.

Create a diagram of the tables and relationships

#### 3.  Explain the difference between a primary and foreign key.

Primary - the unique identifier of each row in a table
Foreign - column or set of keys which match a primary key in another table

### [video] SQL vs NoSQL<sup>3</sup>

#### 1. How do we treat keywords and parameters differently in SQL syntax?

* Keywords are all upper case
* Keywords are reserved words
* not written like objects

#### 2. Define normalization within the context of schemas and data.

Normalization 'cleans things up', organizes the data in the db, relates data among tables, reduces redundancy

#### 3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

One-to-one: one record matches only one other record
One-to-many: one record matches many other records
Many-to-many: many records match many other records

### Bookmarks

[Sequelize API](https://sequelize.org/docs/v6/)

### Footnotes

<sup>1</sup>https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool

<sup>2</sup>https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/

<sup>3</sup>https://www.youtube.com/watch?v=ZS_kXvOeQ5Y

[Back](/reading-notes/401/401-TOC.html)