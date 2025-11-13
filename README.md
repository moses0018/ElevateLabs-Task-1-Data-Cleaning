# Task 1 — Data Cleaning & Preprocessing  
# Elevate Labs Internship Program

# Overview:
This task focuses on cleaning and preprocessing a raw dataset to make it analysis-ready.  
I used the **Mall Customer Segmentation Dataset** and performed all cleaning steps using **Excel Online** and verified using **Jupyter Notebook**.



# Steps Performed

1. Loaded Dataset  
- Imported the CSV file into Excel Online for cleaning.

2. Checked for Missing Values  
- Used filters to check for blanks in each column.  
- No missing values found.

3. Removed Duplicates  
- Applied **Remove Duplicates** on the entire dataset.  
- Dataset contained 0 duplicate rows.

4. Cleaned the Gender Column  
- Used the formula `=PROPER(TRIM(cell))` to standardize values.  
- Replaced original Gender column with cleaned gender values.

5. Cleaned Column Names  
Converted all column headers into a clean, analysis-friendly format:
- `customerid`  
- `gender`  
- `age`  
- `annual_income_k`  
- `spending_score`

6. Corrected Data Types  
- Gender → Text  
- Others → Number  

7. Exported Cleaned Dataset  
Generated `Mall_Customers_cleaned.csv` as the final cleaned output.


# Files in This Repository

- `Mall_Customers.csv` — Original dataset  
- `Mall_Customers_cleaned.csv` — Cleaned dataset  
- `Mall_Customers_Cleaning.ipynb` — Jupyter Notebook  
- `README.md` — Documentation  


## 🛠 Tools Used
- Excel Online (Office 365)  
- Jupyter Notebook  
- GitHub  


## 🎯 Outcome  
The dataset is fully cleaned, standardized, and ready for:
- Exploratory Data Analysis  
- Customer Segmentation  
- Machine Learning modeling  
