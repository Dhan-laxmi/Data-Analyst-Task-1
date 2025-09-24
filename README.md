Data Cleaning and Preprocessing
-------------------------------
## Objective ##

The goal of this task is to clean and preprocess a raw dataset to make it ready for analysis.
Dataset used: Netflix Movies and TV Shows (Kaggle).

## Tools Used ##

Excel (basic cleaning and formatting)

Python (Pandas) (data manipulation and preprocessing)

 ## Steps Performed ##
🔹 Using Excel

Removed duplicates using Data → Remove Duplicates.

Cleaned extra spaces in text fields (e.g., Title column using =TRIM()).

Standardized text formatting (lowercase, uniform naming).

Corrected date formatting into a consistent type (dd-mm-yyyy).

Renamed column headers (e.g., lowercase, no spaces).

## Using Python (Pandas) ##

Loaded the dataset using pd.read_csv().

Checked for missing values with .isnull().sum().

Handled missing values (drop or fill depending on column).

Removed duplicate rows using .drop_duplicates().

Standardized column names (lowercase, snake_case).

Converted data types (e.g., date_added → datetime, release_year → int).

Exported the cleaned dataset back to CSV for further analysis.

## Deliverables ##

netflix_titles_cleaned.csv → Final cleaned dataset.

Short summary of cleaning steps (this README).
