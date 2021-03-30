# SQL

 * SQL is for query, manipulate, and transform data from a database.

 * SQL databases including:
 1. SQLite.
 2. MySQL.
 3. Postgres.
 4. Oracle.
 5. Microsoft SQL.

 * A relational database is a collection of excel-like tables. with a fixed number of named columns (the **attributes** or **properties** of the table) and any number of rows of data (instances).

 ## SQL Lesson 1: SELECT queries.

 ```SQL
/*Select query for a specific columns*/
SELECT column, another_column, …
FROM mytable;
```
```SQL
/*Select query for all columns*/
SELECT * 
FROM mytable;
```

## SQL Lesson 2: Queries with constraints:

```SQL
/*Select query with constraints*/
SELECT column, another_column, …
FROM mytable
WHERE condition
    AND/OR another_condition
    AND/OR …;
```

![WHERE Conditions](/img/WHERE.jpg)

## SQL Lesson 3: Queries with constraints:
* String Conditions:

![string conditions](/img/string-conditions.jpg)

```SQL
/*Select query with constraints*/
SELECT column, another_column, …
FROM mytable
WHERE condition
    AND/OR another_condition
    AND/OR …;
```

## SQL Lesson 4: Filtering and sorting Query results:

```SQL
/*Select query with unique results*/
SELECT DISTINCT column, another_column, …
FROM mytable
WHERE condition(s);
```

### Ordering results:

```SQL
/*Select query with ordered results*/
SELECT column, another_column, …
FROM mytable
WHERE condition(s)
ORDER BY column ASC/DESC;
```

### Limiting results to a subset:

```SQL
/*Select query with limited rows*/
SELECT column, another_column, …
FROM mytable
WHERE condition(s)
ORDER BY column ASC/DESC
LIMIT num_limit OFFSET num_offset;
```





