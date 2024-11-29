
1.Components of a DBMS (Database Management System):

-Database Engine:
Manages data storage, retrieval, and updates. It ensures data consistency, integrity, and security while handling queries and transactions.
-Database Schema:
Describes the structure and organization of data in terms of tables, relationships, and constraints. It serves as a blueprint for how data is stored.
-Query Processor:
Interprets and executes SQL commands from users or applications. It optimizes queries for faster processing.
-Transaction Manager:
Ensures that all database transactions are executed reliably and follow ACID properties (Atomicity, Consistency, Isolation, Durability).
-Metadata Manager:
Maintains data about data (metadata), such as table names, column types, and relationships, ensuring easy navigation and management.
-Database Management Tools:
Provide an interface for database design, administration, monitoring, and maintenance (e.g., backup, recovery, and performance tuning).

2.What is a Relational Database?
A relational database is a type of database that organizes data into structured tables consisting of rows and columns, with relationships established between the tables. Each table represents an entity, and relationships are defined by keys.

Examples:

-MySQL
-PostgreSQL
-Oracle Database
-Microsoft SQL Server

3.Three Classifications of SQL:
->Data Definition Language (DDL):
Defines the structure of the database, such as creating, altering, or deleting tables.
Commands: CREATE, ALTER, DROP, TRUNCATE.
->Data Manipulation Language (DML):
Used to manipulate data within the tables, such as adding, updating, or deleting records.
Commands: INSERT, UPDATE, DELETE, SELECT.
->Data Control Language (DCL):
Manages access control and permissions for database security.
Commands: GRANT, REVOKE.

4.Difference Between Primary Key and Foreign Key:
->Primary Key:
Uniquely identifies each record in a table.
Cannot contain NULL values.
Each table can have only one primary key.
->Foreign Key:
A field in one table that references the primary key in another table.
Used to establish and enforce a link between the two tables.
Can have NULL values.'

5.What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of the data model for a database. It shows entities (tables), attributes (fields), and the relationships (e.g., one-to-one, one-to-many, many-to-many) between them. It helps in database design and understanding data structure.

6.Advantages of Relational Databases:
Data Integrity: Ensures data accuracy and consistency using constraints.
Flexibility: Easy to modify and update the schema without affecting existing data.
Data Relationships: Supports complex queries and relationships between tables.
Standardization: Relational databases use standard SQL for querying and manipulation.
Security: Provides access control and robust user permissions.


7.Four Types of Data Types Used to Store Data in Tables:
->Integer (INT): For whole numbers.
->Character (CHAR, VARCHAR): For text strings.
->Date and Time (DATE, TIMESTAMP): For storing date and time values.
->Decimal (DECIMAL, FLOAT): For numeric values with decimals.


8.Purpose of a Database Management System (DBMS):
-Efficient Data Management: Organizes and stores large amounts of data efficiently.
-Data Retrieval: Facilitates quick and easy retrieval using structured queries.
-Data Integrity and Consistency: Enforces rules to maintain data accuracy.
-Security: Controls access and protects sensitive information.
-Concurrent Access: Allows multiple users to access the database simultaneously without conflicts.
