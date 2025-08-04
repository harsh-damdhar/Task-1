# Task-1
Using Power Query, I performed a series of data preparation steps such as removing duplicates, filtering out invalid rows, splitting and merging columns, standardizing text fields, and converting data types. These transformations made the dataset clean, structured, and analysis-ready without writing a single line of code.

# Hospital Data Cleaning Using Power Query
This project demonstrates how I used **Power Query in Excel** to clean and prepare a dataset titled **Hospital Emergency Room Data**. The dataset contains emergency admission records including patient IDs, admission dates and times, names, and genders.

## 🛠 Tools Used
- Microsoft Excel Power Query Editor  
- Power Query Transformations  
- Data Type Conversion & Formatting
  
## ⚙️ Cleaning Steps Performed:-

### ✅ Removed Duplicates  
- Eliminated any duplicate patient records to ensure data integrity.

### ✅ Filtered Rows  
- Excluded incomplete or irrelevant entries (e.g., rows with null patient IDs or missing timestamps).

### ✅ Split Column by Delimiter  
- Date and time was in one column before.
- split date and time in separate columns. 

### ✅ Renamed Columns  
- Standardized and clarified column names for readability and analysis.

### ✅ Replaced Values  
- Cleaned textual data by replacing inconsistent or erroneous entries
- replace the **gender (M by Male, F by Female)** and **patient satisfaction score (null by 0)**, **patient admission flag (True with Admitted, False with Not Admitted)**

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

## 📸 Screenshots

### ✅ Import CSV File in Power Query
<img width="1598" height="897" alt="import file in power query Screenshot 2025-08-04 162310" src="https://github.com/user-attachments/assets/39222857-e1e5-43a0-994a-cf77b18de09e" />

### ✅ Perform Transformation to File
<img width="1598" height="897" alt="Power query 2 Screenshot 2025-08-04 170650" src="https://github.com/user-attachments/assets/f8ce0448-5d90-4e9a-afeb-6d0db71f4896" />

### ✅ Close and Load Clened File
<img width="1598" height="898" alt="Close and load in Excel Screenshot 2025-08-04 170803" src="https://github.com/user-attachments/assets/fe3b704f-2c6e-44e5-966c-5c21dd79403f" />


## Raw File
<a href="https://github.com/harsh-damdhar/Task-1/blob/main/Raw%20Datasheet.csv">View

## Output CSV File
<a href="https://github.com/harsh-damdhar/Task-1/blob/main/Cleane%20datasheet.csv">View
