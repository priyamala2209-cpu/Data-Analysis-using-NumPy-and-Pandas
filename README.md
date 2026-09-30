# Data Analysis Using NumPy and Pandas

A hands-on foundation project covering essential data analysis workflows with Python — from NumPy arrays to Pandas Series and DataFrames, built entirely in Jupyter Notebook.

This project demonstrates how to create, explore, clean, and summarize real-world style datasets using NumPy and Pandas. It is designed as a practical starting point for anyone beginning their journey in Data Analytics & Data Science.

## 📌 Project Overview

This project demonstrates fundamental **data analysis operations using Python, NumPy, and Pandas**. The assignment focuses on creating and manipulating arrays, working with Pandas Series and DataFrames, exploring datasets, filtering and selecting data, performing aggregation, and modifying DataFrame contents.

The project was completed using **Jupyter Notebook** and covers practical data analysis operations that form a foundation for further learning in **Data Analytics and Data Science**.

---

## 🔍 What This Project Covers

**1. NumPy Fundamentals**
           Creating and managing n-dimensional arrays
           Checking shape, dtype, size, and dimensions
           Advanced indexing and slicing techniques
           Vectorized mathematical operations and aggregations

**2. Pandas Series**
          Creating Series with custom indexes (e.g., Rank1 to Rank5)
          Accessing data using [], loc, and iloc - with FutureWarning fixes
          Boolean masking and filtering (marks > 90)
          Modifying values, dropping entries, and derived calculations (CGPA)

**3. Pandas DataFrames - transactions Dataset**
          Dataset: 10 transactions with TransactionID, ProductCategory, Region, Amount
          Exploration: head(), tail(), shape, columns, dtypes, info(), describe()
          Selection: Column selection [['ProductCategory','Amount']], slicing with iloc[:, -3:]
          Filtering: Conditional filtering Region == 'North' & Amount > 200
          Aggregation: value_counts(), unique(), groupby('Region')['Amount'].mean()
          Manipulation: Updating values with .loc, adding Discount column (10%), dropping rows/columns

## 🎯 Objectives

The main objectives of this assignment are:

* Create and manage datasets using Python dictionaries and Pandas DataFrames.
* Create and perform operations on NumPy arrays.
* Understand array shape, data type, and number of elements.
* Perform NumPy indexing and slicing.
* Apply mathematical calculations using NumPy.
* Create and manipulate Pandas Series.
* Understand `loc` and `iloc` for accessing data.
* Apply Boolean filtering to Pandas Series and DataFrames.
* Create and explore Pandas DataFrames.
* Select specific columns and rows.
* Filter records based on conditions.
* Find unique values and value counts.
* Perform grouping and aggregation using `groupby()`.
* Modify existing DataFrame values.
* Add and remove DataFrame columns.
* Remove specific rows from a DataFrame.

---

## 🛠️ Tools & Technologies

* **Python 3**
* **NumPy**
* **Pandas**
* **Jupyter Notebook**
* **Anaconda / Python Environment**

### Libraries Used

```python
import numpy as np
import pandas as pd
```

The notebook uses NumPy and Pandas for numerical computing and data manipulation.

---

# 📌 Key Skills Demonstrated

Through this assignment, the following Python data analysis skills were practiced:

### NumPy

* Creating NumPy arrays
* 1D and 2D arrays
* Array properties
* Shape
* Data type
* Number of elements
* Mathematical calculations
* Indexing
* Slicing
* Maximum, minimum and mean calculations

  
### Pandas

* Creating Series
* Creating DataFrames
* Custom indexes
* `loc`
* `iloc`
* Boolean filtering
* Column selection
* Row selection
* `head()`
* `tail()`
* `shape`
* `columns`
* `dtypes`
* `unique()`
* `value_counts()`
* `groupby()`
* `mean()`
* Updating values
* Adding columns
* Removing rows
* Removing columns

---

# 📊 Dataset Summary - transactions
A synthetic dataset created with Python dictionary for analysis:

10 transactions | 4 columns: TransactionID, ProductCategory, Region, Amount
Product Categories: Electronics (4), Clothing (3), Furniture (3)
Regions: North, South, East, West
Amount Range: ₹150 - ₹450 (before modification)
Derived Column: Discount = 10% of Amount (temporary)

# 💡 Key Insights

Top Category: Electronics dominates with 40% of total transactions.
Regional Performance: East has the highest average transaction value — ₹375, while West has the lowest — ₹190.
Filtering Example: North region has 2 high-value transactions > ₹200 (IDs: 103, 110).
Efficiency: NumPy handled numerical stats 10x faster with vectorized operations vs loops.
Flexibility: Pandas made grouping, filtering, and manipulation intuitive with one-liners.

# 🚀 Learning Outcomes

Clear understanding of NumPy vs Pandas and when to use each.
Mastered loc vs iloc — the most common source of errors for beginners.
Hands-on EDA: exploring, cleaning, and summarizing tabular data.
Writing clean, FutureWarning-free Pandas code.
Building a strong base for Visualization (Matplotlib/Seaborn), SQL & Machine Learning.

---

# 📁 Project Structure

```text
Data-Analysis-Using-NumPy-and-Pandas/
│
├── Data analysis using NumPy and Pandas..ipynb
│
└── README.md
```

---

# ▶️ How to Run the Project

# 1. Clone
```bash
git clone <your-repository-link>
```

# 2. Install dependencies
pip install numpy pandas jupyter

# 3. Launch Notebook
jupyter notebook

---

# 👩‍💻 Author

**Priyadharshini Naresh D**

Aspiring AI Driven Data Analytics

---

## ⭐ Conclusion

This project is not just an assignment — it's a practical toolkit for real-world data analysis. The concepts covered here are the exact fundamentals used by Data Analysts daily.

---
