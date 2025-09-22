
# Netflix Movies and TV Shows - Data Cleaning

## Objective
Clean and preprocess the raw Netflix dataset to make it consistent, reliable, and analysis-ready.

## Steps Performed
1. **Column Names**
   - Converted to lowercase and replaced spaces with underscores.

2. **Handling Missing Values**
   - Filled `director`, `cast`, `country`, `rating`, and `duration` with "Unknown".
   - Converted `date_added` to datetime format and filled missing values with placeholder date `1900-01-01`.

3. **Removing Duplicates**
   - Dropped duplicate rows.

4. **Data Type Fixes**
   - Converted `release_year` to integer.
   - Ensured `date_added` is datetime type.

5. **Standardization**
   - Duration column standardized: "seasons" → "season".

## Deliverables
- `netflix_titles_cleaned.csv` → Cleaned dataset ready for use.

## Tools Used
- Python (Pandas)
- Jupyter Notebook

---
**Author**: Data Cleaning Task
