## Key Takeaways (Data cleaning is must)

- **#1 Cause of poor quality data = human error**  

- **Dirty data**: data that is incomplete, incorrect, or irrelevant to the problem you're trying to solve. [[What is dirty data?]]

- **Clean data**: data that is complete, correct, and relevant to the problem you're trying to solve.

- **Roles in Data Management**
	- **Data engineers** transform raw data into usable formats and maintain the infrastructure for data processing.
	- **Data warehousing** specialists organize, secure, and back up data to ensure availability and reliability.

- **Null**: an indication that a value does not exist in a dataset.

- **Field**: a single piece of information from a row or column of a spreadsheet.
	- **Data validation**: a tool for checking the accuracy and quality of data before adding or importing it. 
		- **Field length**: a tool for determining how many characters can be keyed into a field.

- **Principles of data integrity**
	- **Validity**
		- Definition: The concept of using data integrity principles to ensure measures conform to defined business rules or constraints.
		- Example: Data collected five years ago used technology that is not approved or supported by the business
	
	- **Accuracy**
		- Definition: The degree of conformity of a measure to a standard or a true value.
		- Example: Addresses in the business database are identified as incorrect when compared to the public postal service database.
	
	- **Completeness**
		- Definition: The degree to which all required measures are known.
		- Example: NULL/missing value for the item “Number of employees per store”.
	
	- **Consistency**
		- Definition: The degree to which a set of measures is equivalent across systems.
		- Example: Date of store opening stored in both MM/DD/YYYY and MM/YY formats

---
## Key Takeaways (First step toward clean data)

- **Removing Unwanted and Irrelevant Data**
	- Make a copy of the dataset before removing any data to avoid losing important information.
	- Remove duplicates that can distort analysis, especially when combining data from multiple sources.
	- Eliminate irrelevant data that does not pertain to the specific problem being solved.

- **Cleaning Text and Formatting**
	- Clear formats: To create a clean and consistent visual appearance for a spreadsheet, which tool ensures all font types, sizes, and colors are uniform.
	- Remove extra spaces and blank cells that can cause sorting and filtering errors.
	- Fix typos, inconsistent capitalization, and punctuation errors using manual edits or spreadsheet tools like spellcheck and autocorrect.
	- Standardize formatting by clearing inconsistent styles from different data sources to create a uniform appearance.

- **Merger**: an agreement that unites two organizations into a single new one.
	- **Data merging**: the process of combining two or more datasets into a single dataset.
	
	- **Compatibility**: how well two or more datasets are able to work together.
	
	- **Challenges of Merging Datasets**
		- Combining datasets from different organizations often leads to inconsistencies, such as different formats for addresses or member IDs.
		- Duplicate records are common because the same individuals may appear in multiple datasets with different identifiers.
	
	- **Key Considerations for Data Merging**
		- Assess whether you have all the necessary data and if it exists within the datasets.
		- Evaluate the compatibility of datasets, including how missing values are handled and how recently data was updated.

	- **Tools and Techniques for Cleaning and Merging**
		- Data analysts use spreadsheet tools, SQL queries, and programming languages like R to clean, merge, and prepare datasets.
		- The choice of tool depends on the complexity of the cleanup and the specific requirements of the project.

- [[Common data-cleaning pitfalls]]

---
## Key Takeaways (Continue cleaning data in spreadsheets) [[Develop your approach to cleaning data]]

- **Conditional Formatting and Highlighting**
	- Conditional formatting changes cell appearance based on set conditions, helping to visually identify data issues like blank cells.
	- Highlighting blank cells allows analysts to quickly spot missing information that needs to be added.

- **Removing Duplicates and Consistent Formatting**
	- The "Remove duplicates" tool automatically finds and deletes duplicate rows to ensure data uniqueness.
	- Formatting tools standardize data appearance, such as converting all dates to a consistent format for easier analysis.

- **Text String Manipulation and Splitting**
	- Text strings are groups of characters in cells; substrings are smaller parts of these strings.
	- The "Split text to columns" tool separates data in one cell into multiple columns based on delimiters like commas, useful for separating combined data such as certifications or fixing numbers stored as text.

- **Concatenate**: a function that join multiple text strings into a single string.

- **Functions for Data Validation**
	- COUNTIF: Counts cells matching a specified condition, useful for identifying values outside expected ranges (e.g., negative numbers or values too high).
	- LEN: Measures the length of text strings to verify data consistency, such as checking if ID codes have the correct number of characters.

- **Functions for Text Manipulation**
	- LEFT and RIGHT: Extract specified numbers of characters from the left or right side of a text string, helpful for isolating parts of codes or identifiers.
	- MID: Extracts a substring from the middle of a text string by specifying a start position and length.

- **Functions for Combining and Cleaning Text**
	- CONCATENATE: Joins two or more text strings into one, useful for recombining separated data elements.
	- TRIM: Removes extra spaces from text, including leading, trailing, and repeated spaces, to clean imported data.

- Additional Tools
	- Conditional Formatting: Highlights cells based on criteria (e.g., length not equal to expected), aiding in quick identification of data issues.

- **Sorting and Filtering**
	- Sorting arranges data in a meaningful order (alphabetical or numerical) to help identify duplicates and find specific data quickly.
	- Filtering shows only data that meets certain criteria, allowing analysts to focus on relevant information for cleaning.

- **Pivot Tables**
	- Pivot tables summarize and reorganize data to provide a clear, clutter-free view.
	- They help analysts focus on specific parts of the dataset, such as identifying the most profitable products by sorting totals.

- **VLOOKUP and Plotting**
	- VLOOKUP is a function that searches for a value in one column and returns related information from another, useful for combining data from multiple sheets.
	- Plotting data in charts or graphs helps identify outliers or errors visually, such as spotting incorrect prices during data cleaning.

- **Data Mapping Overview**
	- Data mapping is the process of matching fields from one database to another to ensure compatibility.
	- It is crucial for successful data migration, integration, and management, especially when different systems store data differently.

- **Steps in Data Mapping**
	- Identify the data to be moved, including tables and fields, and define the desired format for the destination.
	- Map the data fields, which can be simple or complex depending on schemas and keys, using manual methods or specialized software tools.

- **Data Transformation and Validation**
	- Transform data into a consistent format, for example, using functions like concatenate to merge text fields.
	- Transfer data to the destination and perform testing by inspecting samples and using cleaning tools to ensure data is clean and properly formatted.

- **Importance of Data Mapping**
	- Proper data mapping prevents errors from propagating through an organization.
	- It provides a clear roadmap to ensure data arrives safely and is ready for analysis.