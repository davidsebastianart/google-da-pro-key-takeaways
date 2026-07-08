## Key Takeaways (VLOOKUP and data aggregation)

- **Aggregation**: collecting or gathering many separate pieces into a whole.
	- **Data aggregation**: the process of gathering data from multiple sources in order to combine it into a single summarized collection.
	- Puzzle pieces = data
	- Organization = aggregation
	- Pile of pieces = summary
	- Putting the pieces together = gaining insights
	- **Functions help make data aggregation possible.**

- **VLOOKUP (vertical lookup)** searches for a value in one column and returns related information from another column, useful for matching data across spreadsheets.
	- Data Preparation for VLOOKUP
		- Clean data is essential for accurate VLOOKUP results; inconsistent data types like numbers stored as text or dates formatted incorrectly can cause errors.
		- The VALUE function converts text strings representing numbers into numeric values, enabling calculations like SUM to work correctly.
	
	- Common Data Cleaning Tasks
		- Extra spaces in data can cause VLOOKUP errors; the TRIM function removes leading and trailing spaces automatically.
		- Duplicate entries can lead to incorrect matches; using the Remove Duplicates tool helps ensure VLOOKUP finds the correct record.

---
## Key Takeaways (Use JOINS to aggregate data in SQL)

- **JOIN**: a SQL clause that is used to combine rows from two or more tables based on related column.
	![[Pasted image 20260422003131.png]]
	- **INNER JOIN** returns only the records with matching values in both tables, like the overlapping area in a Venn diagram.
	
	- **LEFT JOIN** returns all records from the left table and matching records from the right table, including unmatched left table rows with nulls for right table columns. The table mentioned first is left, and the tables mentioned second is right.
	
	- **RIGHT JOIN** returns all records from the right table and matching records from the left table; it can be simulated by switching table order and using LEFT JOIN.
	
	- **OUTER JOIN (FULL OUTER JOIN)** returns all records from both tables, filling in nulls where there are no matches.

---
## Key Takeaways (Work with subqueries)

- A **subquery** is a SQL query nested inside a larger query, similar to Russian nesting dolls, where multiple layers of queries can be embedded. **The inner query (subquery) executes first**, and **its results are used by the outer query**, allowing complex logic to be combined efficiently in one query.

- **Subqueries and Aggregation Functions**
	- The WHERE clause cannot filter aggregated data, so the HAVING clause is used to filter results after aggregation.
	- CASE statements allow conditional logic within queries to categorize data based on specified criteria.

- **Building Complex Queries with Aliases and Joins**
	- Aliasing tables simplifies query writing and readability, especially in complex queries involving multiple tables.
	- LEFT JOIN is used to include all records from one table (e.g., warehouses) even if there are no matching records in the joined table (e.g., orders).

- **Example: Warehouse Order Fulfillment Analysis**
	- The query calculates the percentage of total orders fulfilled by each warehouse using COUNT and a subquery for total orders.
	- A CASE statement categorizes warehouses based on the percentage of orders they fulfill, and HAVING filters out warehouses with no orders.