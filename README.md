
Netflix Movies and TV Shows - Data Cleaning

Objective
Clean and preprocess the raw Netflix dataset to make it consistent, reliable, and analysis-ready.

Steps Performed

1.Column Names
i.Converted to lowercase and replaced spaces with underscores.

2.Handling Missing Values
i.Filled `director`, `cast`, `country`, `rating`, and `duration` with "Unknown".
ii.Converted `date_added` to datetime format and filled missing values with placeholder date `1900-01-01`.

3.Removing Duplicates
i.Dropped duplicate rows.

4.Data Type Fixes
i.Converted `release_year` to integer.
ii.Ensured `date_added` is datetime type.

5.Standardization
i.Duration column standardized: "seasons" → "season".

Result 
'netflix_titles_cleaned.csv'→ Cleaned dataset ready for use.

Tools Used
- Python (Pandas)
- Microsoft Excel 
