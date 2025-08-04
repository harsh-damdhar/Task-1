# Task-1
Using Power Query, I performed a series of data preparation steps such as removing duplicates, filtering out invalid rows, splitting and merging columns, standardizing text fields, and converting data types. These transformations made the dataset clean, structured, and analysis-ready without writing a single line of code.

# 🏥 Hospital Emergency Room Data Cleaning Using Power Query
This project demonstrates how I used **Power Query in Excel** to clean and prepare a dataset titled **Hospital Emergency Room Data**. The dataset contains emergency admission records including patient IDs, admission dates and times, names, and genders.

## 🛠 Tools Used
- Microsoft Excel Power Query Editor  
- Power Query Transformations  
- Data Type Conversion & Formatting
  
## ⚙️ Cleaning Steps Performed
The following steps were applied using Power Query in Excel:

### ✅ Removed Duplicates  
- Eliminated any duplicate patient records to ensure data integrity.

### ✅ Filtered Rows  
- Excluded incomplete or irrelevant entries (e.g., rows with null patient IDs or missing timestamps).

### ✅ Split Column by Delimiter  
- Patient names were originally in a single column.  
- Split into two parts: **Patient First Initial** and **Patient Last Name** using space as a delimiter.

### ✅ Renamed Columns  
- Standardized and clarified column names for readability and analysis.

### ✅ Replaced Values  
- Cleaned textual data by replacing inconsistent or erroneous entries  
  (e.g., fixing typos in gender or name columns).

### ✅ Removed Unnecessary Columns  
- Dropped irrelevant or redundant columns to focus on key attributes.

### ✅ Merged Columns  
- Recombined split name fields into a unified **Patient Name** field using a space delimiter.

### ✅ Changed Data Types  
- Ensured correct data types for accurate filtering and analysis:
  - `Patient Admission Date` → `Date`
  - `Patient Admission Time` → `Time`
  - `Patient Gender`, `Patient Name` → `Text`

### ✅ Standardized Date Formats  
- Converted all date formats to a consistent **MM/DD/YYYY** style to ensure compatibility with analysis tools.

---

## 📸 Screenshots

Included in this repository are screenshots from Power Query Editor showing:
- Data before and after cleaning  
- Steps applied during transformation  
- Column splitting and merging  

---

## 📁 Output

The cleaned dataset includes the following key columns:
- `Patient Id`
- `Patient Admission Date`
- `Patient Admission Time`
- `Patient Name`
- `Patient Gender`

The dataset is now structur
