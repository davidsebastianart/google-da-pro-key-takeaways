## Key Takeaways (Formatting for better analysis)

- **Incorrectly formatted data can**:
	- Lead to mistakes
	- Take time to fix
	- Affect stakeholder's decision making

- **How to Format Data Types in Spreadsheets**
	- Spreadsheets offer menus to specify data types such as number, currency, date, and percentage to correctly format columns.
	- Using these formatting options helps ensure data is interpreted correctly for sorting and calculations.

- **Converting Units of Measurement** [[Convert data in spreadsheets]]
	- The CONVERT function in spreadsheets allows changing units, for example, converting temperatures from Fahrenheit to Celsius.
	- After applying formulas for conversion, it is recommended to paste values only to lock in the converted data and avoid confusion with formulas.

- **Data Validation**:
	- Add dropdown lists with predetermined options
	- Create customs checkboxes
	- Protect structured data and formulas

- **Conditional formatting**: a spreadsheet tool that changes how cells appears when values meet specific conditions.

- **Using Conditional Formatting with Data Validation**
	- Conditional formatting changes cell appearance based on specific conditions, providing visual cues to quickly understand data.
	- Data validation restricts input types, such as creating drop-down menus or ensuring valid dates, improving data accuracy.

- **Applying Conditional Formatting to Task Status**
	- By applying color codes to the "Status" column with conditional formatting rules, tasks labeled "Not Yet Started," "In Progress," and "Ready" are highlighted in red, yellow, and green respectively.
	- This color-coding allows users to quickly see the progress of tasks at a glance.

- **Tracking Upcoming Deadlines with Dates**
	- Data validation is used to ensure only valid dates are entered in the "Review By This Date" column.
	- Conditional formatting highlights dates after today in orange, making upcoming deadlines easy to identify visually.

---
## Key Takeaways (Combine multiple datasets)

- **Concatenate**: a function that joins together two or more text strings.

- **String Functions Overview**
	- LEN function returns the length of a string, useful for understanding string size.
	- FIND locates the position of a specific character or substring within a string, and is case-sensitive.

- **Applying String Functions to Data**
	- Example uses bike sharing trip data with datetime strings containing both date and time.
	- FIND is used to locate the space character separating date and time, allowing splitting of the string.

- **Extracting Substrings**
	- LEFT and RIGHT functions extract parts of the string from the left or right side respectively.
	- These functions help isolate date or time components into separate columns for analysis.

---
## Key Takeaways (Get support during analysis)

- **Getting Help from Others**
	- Asking peers and mentors for help can provide new solutions and insights to move projects forward.
	- Collaborating with team members can be more productive than trying to solve problems alone.

- **Using Conditional Formulas for Time Calculations**
	- Calculating elapsed time between bike rides can be tricky when the time crosses midnight, causing negative values.
	- A conditional IF formula can handle cases where the end time is less than the start time by adjusting the calculation accordingly.

- **Finding Solutions Online**
	- If team members cannot help, searching online forums and resources can uncover useful formulas and techniques.
	- For example, using the MOD function can convert negative time differences into positive values, solving the calculation problem.

- **Approaching Problems with Thinking Skills**
	- Data analysts use analytical, mathematical, and structured thinking to break down problems into smaller parts and build a mental model.
	- This logical approach helps pinpoint specific questions, making it easier to search for relevant resources online.

- **Using the Right Terms and Tools**
	- Framing questions with appropriate data analytics terminology improves search results and understanding of solutions.
	- Familiarity with basic tools like spreadsheets and SQL is essential to apply online solutions effectively and adapt them to your data.

- **Searching and Applying Online Resources**
	- Online forums and support websites are valuable for finding answers to specific data analysis challenges.
	- Modifying example code or formulas found online to fit your own data is a key skill that enables you to solve problems creatively and efficiently.