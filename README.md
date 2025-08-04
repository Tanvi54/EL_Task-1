# Netflix Movies & TV Shows Dataset - Data Cleaning

This project focuses on **cleaning and preprocessing** the Netflix Movies and TV Shows dataset for analysis and visualization.

---

## Tools Used
- Python (Pandas)
- Colab Notebook

---

## Dataset Information
- **Initial Shape:** `8,807 rows × 12 columns`
- **Final Shape:** `8,807 rows × 14 columns`
- Added new columns: `duration_value`, `duration_unit`

---

## Data Cleaning Steps

1. **Handled Missing Values**  
   - Replaced nulls in `director`, `cast`, `country`, `rating`, `duration`, and `date_added` with meaningful placeholders.

2. **Removed Duplicates**  
   - Dropped duplicate rows to maintain unique records.

3. **Standardized Text Values**  
   - Formatted `type`, `rating`, and `country` columns for consistency.

4. **Formatted Dates**  
   - Converted `date_added` to a uniform `dd-mm-yyyy` format.

5. **Restructured Duration**  
   - Split `duration` into `duration_value` (numeric) and `duration_unit` (minutes/season).

6. **Renamed Columns**  
   - Made all column headers lowercase with underscores for consistency.

7. **Stripped Whitespace**  
   - Removed extra spaces from text fields (`title`, `director`, `cast`, `listed_in`, `description`).

8. **Saved Final Dataset**  
   - Exported the cleaned dataset as `netflix_titles_final_cleaned.csv`.

---

## Final Dataset Highlights
- 0 missing values across all columns.
- Consistent formatting for ratings, countries, and type values.
- Structured duration data for easier analysis.

---

## Output
- **Cleaned dataset:** `netflix_titles_final_cleaned.csv`
