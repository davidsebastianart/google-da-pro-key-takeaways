## Key Takeaways (Work with Spreadsheets)

- **Spreadsheet Tasks:**
	- **Organize your data**
		- Pivot Table
		- Sort and filter
	- **Calculate your data**
		- Formulas
		- Functions

- [[Spreadsheets and the data life cycle]]

- An **attribute** is a characteristic or quality of data used to label a column in a table. It's basically labeling the type of data in each column.

---
## Key Takeaways (Formulas in spreadsheets)

- **Operator**: a symbol that names the type of operation or calculation to be performed.

- **Cell Reference**: a cell or a range of cells in a worksheet that can be used in a formula. A cell reference is composed of the letter of the cell’s column and the number of its row.

- **Range**: a collection of two or more cells

- **Formulas Basics**
	- Formulas in spreadsheets always start with an equal sign (=), indicating a calculation.
	- Autocomplete menus help users create and edit formulas, reducing errors.

- **Mathematical Operators and Auto-filling**
	- Common mathematical operators include subtraction (-), addition (+), division (/), and multiplication (*).
	- The fill handle allows users to auto-fill cells with values or formulas, making data entry more efficient.

- **Absolute Referencing and Data Range**
	- Absolute referencing, marked by a dollar sign ($), keeps cell references constant when copied.
	- Data ranges in formulas are visually represented with colors, helping users identify which cells are included in calculations.

- **[[Spreadsheet errors and fixes]]**
	- '**#DIV/0!**' : a formula is trying to divide a value in a cell by 0 or by an empty cell.
	- '**#ERROR!**' (in Google Sheets only) : a formula can't be interpreted as input (also known as a parsing error).
	- '**#N/A**' : data in a formula can't be found by the spreadsheet.
	- '**#NAME?**' : a formula or function name is'n understood.
	- '**#NUM!**' : a formula or function calculation can't be performed as specified.
	- '**#VALUE!**' : a general error that could indicate a problem with a formula or referenced cells.
	- '**#REF!**' : a formula is referencing a cell that is no longer valid or has been deleted.

---
## Key Takeaways (Functions in spreadsheets)

- **Function**: a preset command that automatically performs a specific process or task using the data.

- **Difference between formulas and functions**
	- A formula is a set of instructions used to perform a calculation using the data in a spreadsheet.
	- A function is a preset command that automatically performs a specific process or task using the data in a spreadsheet.

- **Relative, absolute, and mixed references**
	- Relative references (cells referenced without a dollar sign, like **A2**) will change when you copy and paste the function into a different cell. With relative references, the location of the cell that contains the function determines the cells used by the function.
	
	- Absolute references (cells fully referenced with a dollar sign, like **$A$2**) will not change when you copy and paste the function into a different cell. With absolute references, the cells referenced always remain the same.
	
	- Mixed references (cells partially referenced with a dollar sign, like **$A2** or **A$2**) will change when you copy and paste the function into a different cell. With mixed references, the location of the cell that contains the function determines the cells used by the function, but only the row or column is relative (not both).

---
## Key Takeaways (Save time with structured thinking)

- **Problem domain**: the specific area of analysis that encompasses every activity affecting or affected by the problem. 

- [[02-Ask/Module 1#Key Takeaways (Problem-solving and effective questioning)|Structure Thinking]]

- **Scope of Work (SOW)**: an agreed-upon outline of the work you're going to perform on a project. Examples:
	- Deliverables
	- Timeline
	- Milestones
	- Reports

- A **statement of work** is a document that clearly identifies the products and services a vendor or contractor will provide to an organization. It includes objectives, guidelines, deliverables, schedule, and costs.

- A scope of work is project-based and sets the expectations and boundaries of a project. A scope of work may be included in a statement of work to help define project outcomes.

- Be sure to differentiate **statement of work** from **scope of work**, which are both abbreviated as SOW. Although they help define deliverables and a timeline, they aren't the same and shouldn't be used interchangeably. As a junior data analyst, it's more typical to be asked to create a scope of work than a statement of work.

- [[Practice Assigment Create a scope of work]]

- **Context**: the conditions in which something exists or happens. [[The importance of context]]

- **Understanding Context in Data**
	- Data requires context to be meaningful; actions can be appropriate in some situations but not in others.
	- Contextual interpretation varies among individuals, leading to different conclusions from the same data set.

- **Levels of Data Insights**
	![[Pasted image 20260311234208.png]]
	
	- Data can be descriptive, diagnostic, or predictive, with prescriptive insights being the most valuable for decision-making.
	- Analysts must remain objective and consider all perspectives before drawing conclusions.

- **Recognizing Bias and Limitations**
	- Personal biases can influence data interpretation, making it crucial to ask questions about the data's collection and relevance.
	- Understanding the who, what, where, when, how, and why of data collection helps ensure fairness and accuracy in analysis.
