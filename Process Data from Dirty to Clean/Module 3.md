## Key Takeaways (SQL for sparkling clean data)

- **Importance of SQL**
	- SQL enables quick analysis of large datasets, with modern tools providing near-instant results.
	- Knowing SQL is a fundamental and highly sought-after skill for data analysts, offering a competitive advantage.

- **Introduction to SQL**
	- SQL stands for Structured Query Language, used by data analysts to manage and query databases.
	- It can handle extremely large datasets, processing trillions of rows quickly, unlike spreadsheets.

- **History and Development of SQL**
	- SQL's development began in the 1970s, based on Edgar F. Codd's relational database theory.
	- IBM developed SQL to manipulate data in their System R relational database, and it became a standard language by 1986.

- [[How a junior data analyst uses SQL]]
	- **Similarities between Spreadsheets and SQL**
		- Both allow arithmetic operations, formulas, and joining data to clean and analyze datasets.
		- They can achieve similar results, such as counting specific data points, but SQL handles much larger and more complex datasets.
	
	- **Differences between Spreadsheets and SQL**
		- Spreadsheets are software programs like Excel or Google Sheets with built-in functions, while SQL is a language used to interact with database systems.
		- SQL can access and combine data from multiple sources automatically, making it suitable for large datasets and collaborative work, unlike spreadsheets which are limited to manually input data.
	
	- **Use Cases and Advantages**
		- Spreadsheets are ideal for smaller datasets and individual work, offering handy features like spell check.
		- SQL excels in managing large-scale data, supports multiple database programs, and tracks query changes for team collaboration.

---
## Key Takeaways (Learn basic SQL queries)

- **Basic SQL Queries for Data Extraction**
	- The SELECT query is used to specify and pull specific data columns from a table.
	- Combining SELECT with FROM allows you to extract data from a particular table in a database.

- **Modifying Data in a Database**
	- The INSERT INTO query lets you add new data to a specified table and columns.
	- The UPDATE query allows you to change existing data in a table, with conditions to target specific rows.

- **Managing Tables in a Database**
	- CREATE TABLE IF NOT EXISTS creates a new table in the database if it doesn't already exist.
	- DROP TABLE IF EXISTS is used to delete tables you have created to keep the database clean and organized.

- **Removing Duplicates with SQL**
	- Use the DISTINCT keyword in a SELECT statement to eliminate duplicate rows, ensuring unique results.
	- Example: Selecting unique customer IDs from a table to avoid repeated entries.

- **Cleaning String Variables with SQL Functions**
	- LENGTH (or LEN) function checks the length of string variables to identify inconsistencies.
	- SUBSTRING function extracts parts of strings to standardize entries, such as truncating country codes to two letters.

- **Handling Extra Spaces and Inconsistencies**
	- TRIM function removes extra spaces from string variables to maintain uniformity.
	- Combining TRIM with other functions helps filter and clean data, such as identifying states with extra spaces and correcting them in queries.

- **Understanding Data Type Issues**
	- Imported data may have incorrect data types, such as numbers stored as strings, which can cause sorting and analysis errors.
	- Example: Sorting purchase prices stored as strings results in incorrect order because the database treats them as text.

- **Using the CAST Function**
	- CAST converts data from one type to another, such as from string to float, enabling correct data handling.
	- In the example, purchase_price is cast to FLOAT64 to allow proper numerical sorting in SQL queries.

- **Importance for Data Analysts**
	- Data analysts often work with data from various sources that may require typecasting for accurate analysis.
	- Using CAST early in data cleaning ensures data is usable and reliable for business insights, such as timely sales data analysis.

- **Using CAST for Data Type Conversion**
	- CAST converts data types, such as changing datetime fields to date to simplify output.
	- Example: Filtering purchases in December by casting datetime to date for clearer results.

- **Creating Unique Keys with CONCAT**
	- CONCAT combines strings from multiple columns to create unique identifiers.
	- Example: Combining product_code and product_color to distinguish product variants for inventory analysis.

- **Handling Missing Values with COALESCE**
	- COALESCE returns the first non-null value from a list of columns.
	- Example: Displaying product name if available, otherwise showing product code to handle missing product names.
