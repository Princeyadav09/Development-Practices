SQL Command Categories

![Alt Text](./sql.png)

1. Data Definition Language (DDL):
* CREATE: Creates various database objects like tables, views, indexes, etc.
* ALTER: Modifies the structure of existing database objects.
* DROP: Removes database objects.
* TRUNCATE: Deletes all rows from a table while keeping the table structure.

2. Data Manipulation Language (DML):
* INSERT: Inserts new rows into a table.
* UPDATE: Modifies existing rows in a table.
* DELETE: Deletes rows from a table.
* MERGE: Combines INSERT, UPDATE, and DELETE statements into a single statement for efficient bulk operations.
* COPY: Quickly loads data from an external file into a table.
* BULK UPDATE/DELETE: Similar to MERGE, but specifically designed for updating or deleting large datasets efficiently.

3. Data Control Language (DCL):
* GRANT: Gives permissions to users to access or manipulate database objects.
* REVOKE: Takes away permissions from users.

4. Data Query Language (DQL):
* SELECT: Retrieves data from a database based on specific criteria.

5. Transaction Control Language (TCL):
* COMMIT: Saves the changes made within a transaction (a series of database operations treated as a single unit).
* SAVEPOINT: Creates a named point within a transaction to which you can roll back if needed.
* ROLLBACK: Undoes the changes made within a transaction.

6. Others:
* EXPLAIN: Analyzes and explains the execution plan for a query, helping you understand how the database will process it.
* SET: Sets global database variables or connection properties.
* CALL: Executes a stored procedure, which is a pre-compiled set of SQL statements that can be reused.
* LOCK: Acquires or releases a lock on a database object to control access and prevent conflicts during concurrent modifications.
