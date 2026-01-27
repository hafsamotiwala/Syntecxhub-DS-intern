**Project 3 – Data Cleaning Utility**
**Overview:**

This project focuses on building a simple data cleaning utility using pandas.
The objective is to identify and fix common data quality issues such as missing values, incorrect data types, duplicate records, and inconsistent column names.

Dataset used: Titanic dataset

**Cleaning Steps Performed:**

• Standardized column names (lowercase, underscores)

• Detected missing values across columns

• Handled missing data:

• Filled numerical values using median

• Filled categorical values using mode

• Dropped columns with excessive missing values

• Fixed incorrect data types for numerical and categorical columns

• Removed duplicate rows

• Performed final validation checks

**Output:**

• A cleaned dataset is generated programmatically (titanic_cleaned.csv)

• A brief cleaning log is created to summarize the cleaning process

• Output files are generated locally by running the notebook and are not committed to the repository.

**Key Learnings:**

• Practical handling of missing and inconsistent data

• Importance of data types in analysis

• Writing reproducible and clean data preprocessing code

• Structuring data cleaning workflows step-by-step

**Conclusion:**

This project demonstrates a structured approach to data cleaning using pandas.
It highlights common preprocessing techniques required before performing analysis or building models.
