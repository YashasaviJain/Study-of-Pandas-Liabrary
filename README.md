# Study of Pandas Library

## Student Information

* **Name:** Yashasavi Jain  
* **PRN:** 25070123127  
* **Batch:** B3  

---

## Aim

* To study the basics of the Pandas Library in Python.
* To understand Series and DataFrame.
* To perform basic data operations and statistical analysis using Pandas.

---

## Theory

### What is Pandas?

* Pandas stands for **Panel Data**.
* It is a Python library used for working with structured data.
* It is mainly used for:
  * Data Analysis
  * Data Cleaning
  * Exploratory Data Analysis (EDA)

### Important Data Structures in Pandas

1. **Series**
   * One-dimensional labeled array.
   * Can store integers, strings, floats, etc.

2. **DataFrame**
   * Two-dimensional table.
   * Contains rows and columns.
   * Most commonly used structure in Pandas.

---

## Algorithm

### Step 1: Import Pandas Library

* Import pandas using:
  * `import pandas as pd`

---

### Step 2: Create a Series

* Create a series with values:
  * 10, 20, 30, 40

---

### Step 3: Create a DataFrame

* Create a dictionary with:
  * Name: A, B, C
  * Marks: 85, 90, 78
* Convert dictionary into DataFrame using:
  * `pd.DataFrame()`

---

### Step 4: Display DataFrame Information

* Use:
  * `df.head()` – first 5 rows
  * `df.tail()` – last 5 rows
* Check:
  * `df.shape` – number of rows and columns
  * `df.ndim` – dimension
  * `df.size` – total elements
  * `df.columns` – column names
  * `df.dtypes` – data types

---

### Step 5: Access Data

* Access column:
  * `df["Name"]`
  * `df["Marks"]`
* Access specific value:
  * `df.loc[0,"Name"]`
  * `df.iloc[0,1]`

---

### Step 6: Add New Column

* Add a column named **Grade**
* Conditions:
  * Marks ≥ 90 → Distinction
  * Marks 80–89 → First Class
  * Marks < 80 → Second Class

---

### Step 7: Update Data

* Change marks of student A to 88.
* Modify values using:
  * `df.loc[]`
  * `df.iloc[]`

---

### Step 8: Delete Column

* Remove Grade column using:
  * `df.drop("Grade", axis=1)`

---

### Step 9: Perform Statistical Analysis

* Calculate:
  * Mean → `df["Marks"].mean()`
  * Minimum → `df["Marks"].min()`
  * Maximum → `df["Marks"].max()`

---

### Step 10: Apply Filtering

* Display students scoring more than 80:
  * `df[df["Marks"] > 80]`

---

## Conclusion

* Pandas is a powerful and easy-to-use library for data analysis.
* It helps in handling structured data efficiently.
* We learned:
  * Creating Series and DataFrame
  * Accessing and modifying data
  * Performing statistical operations
  * Applying conditions and filtering
* Pandas makes data handling simple and organized.

---

# NOTE

* Use **Run All** option while executing the notebook.
