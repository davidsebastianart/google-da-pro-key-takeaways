## Key Takeaways (Get started with data calculations)

- **Using Formulas for Basic Calculations**
	- Formulas in spreadsheets start with an equal sign and can include functions like SUM to add data across cells.
	- The fill handle is a shortcut tool to quickly copy formulas across rows or columns, saving time and ensuring accuracy.

- **Calculating Sales Trends**
	- Summing monthly sales data by year helps find annual sales totals.
	- Calculating year-over-year sales growth involves subtracting totals from consecutive years and then finding the growth rate by dividing the difference by the previous year's total.

- **Analyzing Monthly Sales Averages and Visualization**
	- The AVERAGE function calculates average sales per month to identify trends.
	- Conditional formatting applies color scales to highlight higher and lower sales visually, aiding quick interpretation.

- **Finding Minimum and Maximum Values**
	- MIN and MAX functions identify the lowest and highest average monthly sales, providing insights into sales performance extremes.

- **COUNTIF Function**
	- COUNTIF counts the number of cells that meet a specified condition, such as counting transactions with exactly one item.
	- It helps identify and quantify specific data points, useful for summarizing and cleaning data.

- **SUMIF Function**
	- SUMIF adds numeric values in a range based on a given condition, like summing revenue from transactions with one item.
	- The formula includes the range to evaluate, the condition, and the range to sum, allowing targeted aggregation of data.

- **Understanding SUMPRODUCT**
	- SUMPRODUCT multiplies corresponding values in two or more arrays and returns the sum of those products.
	- An array is a collection of values in cells, not the cells themselves.

- **Using SUMPRODUCT for Revenue Calculation**
	- It can calculate total revenue by multiplying quantities sold by unit prices and summing the results in one formula.
	- This saves time compared to multiplying each pair individually and then adding them up.

- **Applying SUMPRODUCT for Profit Margin**
	- The function can also incorporate a third array, such as profit margin percentages, to calculate total profit.
	- This avoids manual multiplication of revenue by profit margin for each product and summing the results.

---
## Key Takeaways (Pivot...pivot...pivot...)

- **Pivot Tables for Data Organization** [[Elements of a pivot table]]
	- Pivot tables allow viewing data in multiple ways to find insights and trends, such as sorting and grouping data by year.
	- Grouping dates by year in the pivot table helps summarize data at the desired level of detail.

- **Using Pivot Tables for Calculations**
	- Pivot tables can automatically calculate sums, averages, counts, and other summary statistics without writing formulas.
	- In the example, total box office revenue per year and average revenue per movie are calculated using pivot table functions.

- **Analyzing Data with Pivot Tables** [[Use pivot tables in analysis]]
	- Adding multiple values to a pivot table enables deeper analysis, such as comparing total revenue and average revenue.
	- Filters and calculated fields can be used to test hypotheses and answer additional questions, like identifying movies earning less than a certain amount in a specific year.

- **Using Filters in Pivot Tables**
	- Filters allow viewing specific data values; here, a filter was applied to show movies earning less than $10 million.
	- Filtering revealed that 20 movies in 2015 earned under $10 million, which was a high number compared to other years.

- **Calculated Fields and Verification**
	- Calculated fields are custom columns in pivot tables that perform calculations based on other fields.
	- A calculated field was created to verify the average revenue of movies under $10 million, ensuring data accuracy after filtering.

- **Percentage Analysis and Interpretation**
	- A formula was added outside the pivot table to calculate the percentage of movies earning less than $10 million each year.
	- The analysis showed 16% of 2015 movies earned less than $10 million, explaining the lower average revenue that year compared to about 10% in other years.

---
## Key Takeaways (Learn more SQL calculations)

- **Arithmetic Operators in SQL and Spreadsheets**
	- Both use the same basic arithmetic operators: plus (+) for addition, minus (-) for subtraction, asterisk (*) for multiplication, and forward slash (/) for division.
	- SQL queries embed these operators to perform calculations on data pulled from databases, similar to spreadsheet formulas.

- **Writing SQL Queries for Calculations**
	- A typical query starts with SELECT, followed by column names and operators, then AS to name the result column, and FROM to specify the data table.
	- Parentheses control the order of operations when multiple operators are used, just like in spreadsheets.

- **Functions and Special Operators**
	- SQL uses aggregate functions like SUM and AVG, similar to spreadsheet functions, to perform calculations on sets of data.
	- The modulo operator (%) in SQL returns the remainder of a division, comparable to the MOD function in spreadsheets.

- **Basic SQL Calculation Syntax**
	- Use SELECT to specify columns, include calculations with operators (e.g., +, /), and label new columns with AS.
	- Finish queries with FROM and the table name to pull data.

- **Example with Avocado Sales Data**
	- Calculate total bags sold by adding Small_Bags, Large_Bags, and XLarge_Bags columns.
	- Compare calculated totals with existing Total_Bags column to verify data accuracy.

- **Calculating Percentages and Handling Errors**
	- Calculate percentage of small bags by dividing Small_Bags by Total_Bags and multiplying by 100.
	- Use WHERE clause to exclude rows where Total_Bags is zero to avoid division by zero errors.
	- Alternative methods like safe divide functions can also prevent such errors.

- **GROUP BY Command**
	- GROUP BY groups rows with the same values into summary rows, used with SELECT statements.
	- It helps organize data by categories, such as grouping bike rides by year.

- **Using Aggregate Functions**
	- Aggregate functions like COUNT and SUM perform calculations on grouped data.
	- Example: COUNT(*) counts all rows in each group to find the total number of rides per year.

- **ORDER BY Command**
	- ORDER BY sorts the grouped results, by default in ascending order.
	- You can specify DESC to sort in descending order, helping to organize the output for easier interpretation.

---
## Key Takeaways (The data-validation process)

- **Data Validation Function and Process**
	- Data validation in spreadsheets adds drop-down lists to cells to control input and protect structured data and formulas.
	- The data validation process involves continuous checking to ensure data is complete, accurate, secure, and consistent throughout analysis.

- **Practical Examples of Data Validation**
	- Example of checking purchase price calculations in a furniture retailer dataset revealed discounts that affect data interpretation.
	- Common sense checks, like verifying no sales on weekends for a weekday-only business, help avoid miscalculations and clarify data context.

- **Using Data Validation in Different Tools**
	- Data validation is essential regardless of the analysis tool, including spreadsheets and SQL.
	- SQL queries can be used to verify data accuracy, such as confirming totals match component sums and handling errors like division by zero to prevent misleading results.

---
## Key Takeaways (SQL and temporary tables)

- **What Are Temporary Tables**
	- Temporary tables are database tables created temporarily on a server to store subsets of data for a short time.
	- They are automatically deleted at the end of a database session and are useful for short-term analysis tasks like calculations.
	
	- **Benefits and Use Cases of Temporary Tables**
		- Temporary tables help simplify complex queries by storing intermediate results, such as joining smaller tables first before joining larger ones.
		- They allow combining results from multiple databases or repeatedly working with a filtered subset of data without re-filtering each time.
	
	- **Creating and Using Temporary Tables in SQL**
		- Different database systems have different ways to create temporary tables; this example uses BigQuery's WITH clause to create a temporary table.
		- The WITH clause defines a temporary table that can be queried multiple times within the same query session, improving efficiency and readability.
	
	- **Practical Example**
		- A temporary table is created to store bike trips lasting 60 minutes or longer.
		- Multiple queries can then be run on this temporary table without repeatedly filtering the original data.
	
	- **Advantages for Analysts and Teams**
		- Using temporary tables makes work more efficient by reducing repetitive code and simplifying complex queries.
		- Temporary tables also make code easier to read and understand, benefiting team collaboration.

- **Temporary Table Creation Methods** [[Work with temporary tables]]
	- WITH clause creates temporary tables to keep SQL code organized and efficient.
	- SELECT INTO copies data into a new temporary table without adding it to the database, useful for specific queries with conditions.
	
	- **CREATE TABLE Statement**
		- CREATE TABLE adds the new table to the database, making it accessible to multiple users.
		- It allows adding metadata to describe the table, which helps others understand the data.
	
	- **Choosing the Right Method and Considerations**
		- The choice between WITH, SELECT INTO, and CREATE TABLE depends on your needs and the database system.
		- Temporary tables improve query readability and reduce errors, though creating them may sometimes interrupt workflow.