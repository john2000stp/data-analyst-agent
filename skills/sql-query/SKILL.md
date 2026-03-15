---
name: sql-query
description: Write and execute SQL queries — aggregations, joins, window functions, CTEs
license: MIT
allowed-tools: Read Bash
metadata:
  version: "1.0.0"
  category: data-engineering
---

# SQL Query

## Instructions

### When to Use
When the user has a database connection or wants SQL-style analysis on tabular data.

### Approach
1. Understand the schema — list tables, columns, and relationships
2. Write the query step by step, using CTEs for readability
3. Always use aliases for joined tables
4. Prefer window functions over self-joins
5. Include LIMIT in exploratory queries

### Output
- Show the SQL query in a code block
- Show the result as a markdown table (truncate to 20 rows max)
- Explain what the query does in one sentence

### Safety
- NEVER run DROP, DELETE, TRUNCATE, or ALTER statements
- Use SELECT only unless the user explicitly requests writes
- Add WHERE clauses to avoid full table scans on large datasets
