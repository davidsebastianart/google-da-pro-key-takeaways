## Key Takeaways (Organize data for analysis)

- **Analysis**: the process used to make sense of the data collected.
	- **The goal of analysis** is to identify trends and relationships within data so you can accurately answer the question you're asking.
	
	- **The 4 phases of analysis:**
		1. **Organize data**. [[Sort and filter data to keep it organized]]
			Organize data to prepare it for exploration and ensure it is clean and ready for analysis.
		
		2. **Format and adjust data**
			Format and adjust data by sorting and filtering to make it easier to reference and work with.
		
		3. **Get input from others**
			Seek input from others to gain different perspectives and avoid potential challenges. Use collaborative information, such as others' actions or feedback, to inform your decisions.
		
		4. **Transform data**
			Identify relationships and patterns within the data. Perform calculations and make decisions based on these insights to solve the problem at hand.

- **Sorting**: when you arrange data into a meaningful order to make it easier to understand, analyze, and visualize. Sorting arranges data in a meaningful order based on a chosen metric, such as price, alphabetical order, date, or distance.

- **Filtering** displays only data that meets specific criteria, narrowing down large datasets to relevant subsets.

---
## Key Takeaways (Sort data in spreadsheets)

- **Sort sheet**: all of the data in a spreadsheet is sorted by the ranking of a specific sorted column - data across rows is kept together.

- **Sort range**: nothing else on the spreadsheet is rearranged besides the specific cells in a column.

- **Sorting Methods in Spreadsheets**
	- Two main ways to sort data: using the Data tab menu and writing a SORT function.
	- The SORT function requires specifying the data range, the column number to sort by, and whether the order is ascending (TRUE) or descending (FALSE).

- **Using the SORT Function**
	- Example given with a party guest list sorted by table number using the SORT function.
	- The function syntax includes referencing the data range and sorting column by number, not letter.

- **Custom Sort Orders**
	- Custom sort orders allow sorting by multiple conditions sequentially.
	- Example: sorting guests first by whether they received an invitation, then alphabetically by name using the "Sort range" option under the Data tab.

---
## Key Takeaways (Sort data using SQL)

- **Sorting Data with SQL**
	- The ORDER BY clause is used to sort query results by one or more columns, with ascending order as the default.
	- Sorting can be done in descending order by adding DESC after the column name in the ORDER BY clause.

- **Filtering and Combining Sorts in SQL**
	- The WHERE clause filters data to include only rows that meet specified conditions.
	- Filters can be combined with sorting, for example, filtering movies by genre and sorting by release date.

- **Advanced Filtering with Multiple Conditions**
	- The AND operator allows filtering data based on multiple conditions simultaneously.
	- An example is filtering for comedy movies with box office revenue over $300 million, then sorting by release date in descending order.
