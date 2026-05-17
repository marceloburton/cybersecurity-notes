# 🗄️ Databases and SQL (Module 4)

## 📌 Databases

A **database** is an organized collection of information or data.

### Databases:
- Store large amounts of information
- Support multiple users accessing data simultaneously
- Handle complex operations efficiently

---

## 📊 Spreadsheets vs Databases

### Spreadsheets
- Designed for a single user or small team
- Store smaller amounts of data
- Better for simpler tasks

### Databases
- Handle significantly larger datasets
- Support multiple users at once
- More efficient for organizing and querying information

---

# 🧩 Relational Databases

A **relational database** organizes information into related tables.

## Key Components

### Tables
Store organized data.

### Columns (Fields)
Contain categories of information.

### Rows (Records)
Contain individual entries of data.

---

## 🔑 Keys in Relational Databases

Tables can be connected through shared columns called **keys**.

### Primary Key
A column where every row contains a unique value.

#### Rules:
- Cannot contain duplicates
- Cannot contain NULL or empty values

---

### Foreign Key
A column that references a primary key from another table.

#### Rules:
- Can contain duplicates
- Can contain NULL values
- Used to connect related tables

---

# 💻 Structured Query Language (SQL)

## SQL

**Structured Query Language (SQL)** is a programming language used to create, manage, and retrieve data from databases.

### Common Uses
- Retrieving logs
- Filtering data
- Organizing records
- Connecting tables
- Performing calculations

---

## Query

A **query** is a request for information from one or more database tables.

---

## Logs

A **log** is a record of events occurring within an organization's systems.

---

# 🐧 Accessing SQL in Linux

SQL can be accessed through the Linux command line.

### SQLite Example

```bash
sqlite3
```

After entering SQL mode, commands are interpreted as SQL queries instead of Linux commands.

---

# 🔍 Linux Filtering vs SQL Filtering

## Linux Filtering

Used for:
- Searching files
- Managing permissions
- Filtering command output
- Managing processes

### Common Linux Tools
- `grep`
- `find`
- `sed`
- `cut`

---

## SQL Filtering

Used for:
- Querying database records
- Filtering table data
- Retrieving specific information

### Common SQL Keywords
- `SELECT`
- `WHERE`
- `JOIN`

---

# 🏗️ SQL Structure Advantages

Compared to Linux text output, SQL:
- Organizes data into columns and rows
- Makes information easier to read
- Allows faster filtering and analysis
- Supports joining multiple tables together

---

# 🔗 Joining Tables

SQL can connect multiple tables using shared columns.

Linux does not naturally support relational table connections like SQL databases do.

---

# 📌 SQL Keywords

## `SELECT`

Specifies which columns to return.

### Example

```sql
SELECT employee_id, device_id
FROM employees;
```

---

## `SELECT *`

Returns all columns from a table.

### Example

```sql
SELECT *
FROM employees;
```

---

## `FROM`

Specifies which table to query.

---

# 🧠 SQL Syntax Basics

## Syntax Rules

- SQL keywords are not case-sensitive
- Capitalizing keywords improves readability
- Statements end with semicolons (`;`)
- `*` means "all"
- Line breaks improve readability but are optional

---

# 📑 Sorting Results

## `ORDER BY`

Sorts query results based on one or more columns.

---

## Ascending Order (Default)

### Example

```sql
SELECT customerid, city, country
FROM customers
ORDER BY city;
```

---

## Descending Order

Uses the `DESC` keyword.

### Example

```sql
SELECT customerid, city, country
FROM customers
ORDER BY city DESC;
```

---

## Sorting by Multiple Columns

### Example

```sql
SELECT customerid, city, country
FROM customers
ORDER BY country, city;
```

SQL first sorts by country, then sorts matching countries by city.

---

# 🎯 Filtering Data

## Filtering

Selecting data that matches a specific condition.

---

## Operator

A symbol or keyword representing an operation.

### Example

```sql
country = 'USA'
```

---

# 📌 `WHERE`

Specifies filtering conditions.

### Example

```sql
SELECT *
FROM log_in_attempts
WHERE country = 'USA';
```

Returns only rows where the country is USA.

---

# 🔎 Pattern Matching

## Wildcards (`%`)

Used to search for patterns instead of exact matches.

### Example

```sql
WHERE office LIKE 'East%'
```

Returns:
- East-120
- East-290
- East-435

---

## `LIKE`

Used with `WHERE` for pattern matching.

### Example

```sql
SELECT *
FROM log_in_attempts
WHERE country LIKE 'US%';
```

---

# 🧾 Common Data Types

## String

Text-based data.

### Example

```text
analyst10
```

---

## Numeric

Number-based data.

### Examples
- Login attempt counts
- IDs
- Calculations

---

## Date and Time

Stores dates and timestamps.

---

# ⚙️ SQL Operators

| Operator | Meaning |
|---|---|
| `=` | Equal to |
| `>` | Greater than |
| `<` | Less than |
| `<>` | Not equal to |
| `>=` | Greater than or equal to |
| `<=` | Less than or equal to |

---

## Example: Time Filtering

```sql
SELECT *
FROM log_in_attempts
WHERE time > '18:00';
```

---

# 📆 `BETWEEN`

Filters values within a range.

### Example

```sql
SELECT *
FROM machines
WHERE OS_patch_date BETWEEN '2021-03-01' AND '2021-09-01';
```

---

# 🔗 Logical Operators

## `AND`

Both conditions must be true.

### Example

```sql
SELECT *
FROM machines
WHERE operating_system = 'OS 1'
AND email_client = 'Email Client 1';
```

---

## `OR`

Either condition can be true.

### Example

```sql
SELECT *
FROM machines
WHERE operating_system = 'OS 1'
OR operating_system = 'OS 3';
```

---

## `NOT`

Negates a condition.

### Example

```sql
SELECT *
FROM machines
WHERE NOT operating_system = 'OS 3';
```

---

# 🔄 Joining Tables

When working with multiple tables, SQL may require specifying the table name before the column.

### Example

```sql
employees.employee_id
machines.employee_id
```

---

# 🔗 `INNER JOIN`

Returns rows with matching values in both tables.

### Example

```sql
SELECT username, office, operating_system
FROM employees
INNER JOIN machines
ON employees.employee_id = machines.employee_id;
```

---

# 🌐 Outer Joins

Outer joins return unmatched rows as `NULL`.

---

## `LEFT JOIN`

Returns:
- All rows from the first table
- Matching rows from the second table

### Example

```sql
SELECT *
FROM employees
LEFT JOIN machines
ON employees.employee_id = machines.employee_id;
```

---

## `RIGHT JOIN`

Returns:
- All rows from the second table
- Matching rows from the first table

### Example

```sql
SELECT *
FROM employees
RIGHT JOIN machines
ON employees.employee_id = machines.employee_id;
```

---

## `FULL OUTER JOIN`

Returns:
- All rows from both tables
- Unmatched values shown as `NULL`

### Example

```sql
SELECT *
FROM employees
FULL OUTER JOIN machines
ON employees.employee_id = machines.employee_id;
```

---

# 📊 Aggregate Functions

Aggregate functions perform calculations across multiple rows.

---

## `COUNT()`

Returns the number of rows.

### Example

```sql
SELECT COUNT(firstname)
FROM customers;
```

---

## `AVG()`

Returns the average value from a numeric column.

---

## `SUM()`

Returns the total value from a numeric column.

---

# 📌 Aggregate Function with Filtering

### Example

```sql
SELECT COUNT(firstname)
FROM customers
WHERE country = 'USA';
```

---

# 🧠 Key Takeaways

- Databases organize and manage large amounts of structured information
- Relational databases use tables connected through keys
- SQL is used to retrieve, filter, organize, and analyze database data
- `SELECT`, `FROM`, and `WHERE` are foundational SQL keywords
- `ORDER BY` sorts query results
- `LIKE` allows pattern matching using wildcards
- Logical operators such as `AND`, `OR`, and `NOT` refine filtering conditions
- SQL joins combine data from multiple related tables
- Aggregate functions like `COUNT`, `AVG`, and `SUM` perform calculations across datasets
- SQL is an essential cybersecurity skill for investigating logs and analyzing security data
