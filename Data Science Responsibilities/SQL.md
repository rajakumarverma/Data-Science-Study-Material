Certainly! Here's a quick reference guide for common SQL (Structured Query Language) commands and statements:

### Basic SQL Commands:

1. **SELECT:**
   - Retrieve data from one or more tables.
   ```sql
   SELECT column1, column2 FROM table_name WHERE condition;
   ```

2. **INSERT:**
   - Insert new records into a table.
   ```sql
   INSERT INTO table_name (column1, column2) VALUES (value1, value2);
   ```

3. **UPDATE:**
   - Modify existing records in a table.
   ```sql
   UPDATE table_name SET column1 = value1 WHERE condition;
   ```

4. **DELETE:**
   - Remove records from a table.
   ```sql
   DELETE FROM table_name WHERE condition;
   ```

### Table Operations:

5. **CREATE TABLE:**
   - Create a new table with specified columns and data types.
   ```sql
   CREATE TABLE table_name (
       column1 datatype,
       column2 datatype,
       ...
   );
   ```

6. **ALTER TABLE:**
   - Modify an existing table (add, modify, or drop columns).
   ```sql
   ALTER TABLE table_name
   ADD column_name datatype;

   ALTER TABLE table_name
   MODIFY column_name datatype;

   ALTER TABLE table_name
   DROP COLUMN column_name;
   ```

7. **DROP TABLE:**
   - Delete an existing table.
   ```sql
   DROP TABLE table_name;
   ```

### Data Retrieval:

8. **WHERE Clause:**
   - Filter results based on a specified condition.
   ```sql
   SELECT * FROM table_name WHERE condition;
   ```

9. **ORDER BY:**
   - Sort the result set by one or more columns.
   ```sql
   SELECT * FROM table_name ORDER BY column1 ASC, column2 DESC;
   ```

10. **GROUP BY:**
    - Group rows that have the same values in specified columns.
    ```sql
    SELECT column1, COUNT(*) FROM table_name GROUP BY column1;
    ```

### Advanced Queries:

11. **JOIN:**
    - Combine rows from two or more tables based on a related column.
    ```sql
    SELECT * FROM table1
    INNER JOIN table2 ON table1.column = table2.column;
    ```

12. **SUBQUERIES:**
    - Use a query inside another query.
    ```sql
    SELECT column FROM table WHERE column IN (SELECT column FROM another_table);
    ```

13. **UNION:**
    - Combine results of two or more SELECT statements.
    ```sql
    SELECT column FROM table1
    UNION
    SELECT column FROM table2;
    ```

### Data Modification and Transactions:

14. **COMMIT:**
    - Save changes made during the current transaction.
    ```sql
    COMMIT;
    ```

15. **ROLLBACK:**
    - Undo changes made during the current transaction.
    ```sql
    ROLLBACK;
    ```

16. **SAVEPOINT:**
    - Set a point within a transaction to which you can later roll back.
    ```sql
    SAVEPOINT savepoint_name;
    ```

This is a basic overview, and there's much more to SQL, including functions, stored procedures, triggers, and more. Feel free to ask if you have specific questions or need further clarification!
