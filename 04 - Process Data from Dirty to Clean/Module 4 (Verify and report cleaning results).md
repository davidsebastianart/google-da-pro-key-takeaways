## Key Takeaways (Manually cleaning data)

- **Changelogs** are files containing chronologically ordered lists of modifications made to a project. They are usually organized by version and include the date followed by a list of added, improved, and removed features.

- **Verification**: a process to confirm that a data-cleaning effort was well-executed and the resulting data is accurate and reliable. [[Data-cleaning verification checklist]]
	- It involves comparing the cleaned data against the original unclean data to identify and fix issues like null values or misspellings.

- **See the big picture when verifying data-cleaning**:
	1. **Consider the business problem**
	2. **Consider the goal**
	3. **Consider the data**

- **Data Quality Checks**
	- Analysts should assess whether the data can solve the problem and meet project goals by reviewing data sources and cleaning steps.
	- Getting feedback from others and looking for anomalies, such as unexpected duplicate responses, helps catch errors early.

---
## Key Takeaways (Document the cleaning process)

- **Documentation**: the process of tracking changes, additions, deletions, and errors involved in your data cleaning effort. It helps **recover from data-cleaning errors, informs other users of changes (when the data errors are fixable, the documentation needs to record how the data was fixed), and assesses data quality for analysis.**

- A **changelog** is a chronological record of modifications made to a data project. [[Embrace changelogs]]
	- In spreadsheets, version history and cell edit history features allow tracking changes and identifying who made them.
	- In SQL, changelogs depend on the software; comments and query history help track and revert changes.

- **Benefits of Documentation and Reporting**
	- Documentation provides a reference for future data cleaning efforts and team members taking over the project.
	- It warns about data sets with many errors and supports decisions to use alternative data sources.
	- Reporting on cleaning results helps communicate changes effectively to stakeholders.