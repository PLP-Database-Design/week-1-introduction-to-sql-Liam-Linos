Database Engine:

Purpose: Manages data storage, retrieval, and update.

Function: Executes queries, handles transactions, and ensures data integrity and consistency.

Database Schema:

Purpose: Defines the logical structure of the database.

Function: Specifies tables, columns, data types, and relationships between tables.

Query Processor:

Purpose: Interprets and executes database queries.

Function: Translates SQL queries into executable instructions for the database engine.

Transaction Manager:

Purpose: Manages database transactions.

Function: Ensures ACID (Atomicity, Consistency, Isolation, Durability) properties of transactions.

Storage Manager:

Purpose: Manages physical storage of data.

Function: Allocates space on disk, manages data files, and ensures efficient storage access.

Metadata Manager:

Purpose: Manages metadata (data about data).

Function: Maintains information about database schema, indexes, constraints, and other database objects.

Database Administrator (DBA):

Purpose: Oversees and maintains the database system.

Function: Ensures database security, performance, and availability.

What is a Relational Database?
A relational database is a type of database that stores data in tables (relations) with rows and columns. It uses structured query language (SQL) for data manipulation and retrieval.

Examples:

MySQL

PostgreSQL

SQLite

Microsoft SQL Server

Classifications of SQL:
DDL (Data Definition Language):

Purpose: Defines database schema and objects.

Commands: CREATE, ALTER, DROP.

DML (Data Manipulation Language):

Purpose: Manipulates data within database objects.

Commands: SELECT, INSERT, UPDATE, DELETE.

DCL (Data Control Language):

Purpose: Controls access to the data.

Commands: GRANT, REVOKE.

Primary Key vs. Foreign Key:
Primary Key:

Purpose: Uniquely identifies each row in a table.

Characteristics: Must be unique and not null.

Example: student_id in a Students table.

Foreign Key:

Purpose: Establishes a relationship between tables.

Characteristics: Refers to the primary key of another table.

Example: student_id in an Enrollments table, referencing student_id in Students.

Entity-Relationship Diagram (ERD):
An Entity-Relationship Diagram (ERD) is a visual representation of the relationships between entities in a database. It depicts entities, attributes, and the relationships (e.g., one-to-one, one-to-many) between them.

Advantages of Relational Databases:
Data Integrity:

Enforces data integrity through constraints and keys.

Flexibility:

Supports complex queries and transactions.

Scalability:

Can handle large volumes of data efficiently.

Normalization:

Reduces data redundancy and ensures consistency.

Types of Data Types Used in Tables:
Integer (INT):

Stores whole numbers.

Varchar (VARCHAR):

Stores variable-length strings.

Date (DATE):

Stores date values.

Boolean (BOOLEAN):

Stores true/false values.

Purpose of a Database Management System (DBMS):
The primary purpose of a DBMS is to provide an efficient and reliable means of managing, storing, and retrieving data. It ensures data integrity, security, and accessibility while facilitating concurrent access by multiple users. A DBMS also enables data manipulation and analysis through a structured query language (SQL), supporting decision-making and operational processes within an organization.
