#  Sales Data Cleaning & Analysis Project

## Project Overview
This project focuses on cleaning and analyzing sales data using Python and Pandas.  
The dataset contained missing values, inconsistent date formats, duplicate records, 
and validation issues which were resolved through systematic data preprocessing.

---

##  Tools & Technologies Used
- Python
- Pandas
- Jupyter Notebook

---

##  Data Cleaning Steps Performed
- Converted date columns from object to datetime
- Handled mixed date formats using `pd.to_datetime()`
- Managed missing values (NaN / NaT)
- Merged multiple datasets using `merge()`
- Resolved duplicate columns using `combine_first()`
- Validated discount percentage values
- Removed unnecessary columns
- Checked for duplicate records

---

##  Exploratory Data Analysis (EDA)
- Generated summary statistics using `describe()`
- Calculated city-wise revenue using `groupby()`
- Identified top-performing cities by total sales
- Checked date range using `min()` and `max()`

---

##  Key Insights
- Identified highest revenue generating cities
- Standardized inconsistent date formats
- Ensured clean and analysis-ready dataset

---

##  Files Included
- `sales_data_analysis.ipynb` → Jupyter Notebook
- `full_data_cleaning_practice_dataset.csv` → Cleaned dataset
- `README.md` → Project documentation

---

##  Conclusion
This project demonstrates real-world data cleaning and preprocessing techniques used in 
data analytics workflows. It prepares raw business data for accurate reporting and analysis.
