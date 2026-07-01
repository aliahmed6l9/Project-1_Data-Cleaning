````markdown
# 🧹 Data Cleaning & Preprocessing using Python (Pandas)

## 📊 Data Analytics Internship Project – DecodeLabs

A complete **Data Cleaning & Preprocessing** project performed on a raw transactional dataset using **Python**, **Pandas**, and **Jupyter Notebook**. The project focuses on improving data quality, handling missing values, validating business rules, and preparing the dataset for **Exploratory Data Analysis (EDA)**.

---

# 📖 Project Overview

Data cleaning is one of the most critical stages in the data analytics lifecycle. This project demonstrates a complete end-to-end workflow for transforming raw data into a clean, structured, and analysis-ready dataset.

The dataset consists of **1,200 transactional records** containing customer purchases and related information. Throughout the project, several preprocessing techniques were applied to improve data consistency, integrity, and usability.

### 🔍 Key Implementations

- 📥 Data Import & Exploration
- 🔎 Missing Value Analysis
- 🔄 Duplicate Detection
- 🧹 Text Cleaning & Standardization
- 📅 Data Type Validation
- ✅ Business Rule Validation
- 📈 Outlier Detection
- 📊 Data Quality Assessment
- 📤 Dataset Export

---

# 🎯 Project Objectives

- Import and inspect the raw dataset.
- Identify missing values and inconsistencies.
- Clean and standardize textual data.
- Handle missing values appropriately.
- Detect duplicate records.
- Validate business rules and calculated fields.
- Detect potential outliers.
- Prepare a clean dataset for Exploratory Data Analysis (EDA).
- Export the cleaned dataset for further analysis.

---

# ✨ Features

## 📂 Data Exploration

- Dataset Overview
- Shape & Dimensions
- Column Information
- Summary Statistics

## 🧹 Data Cleaning

- Missing Value Identification
- Missing Value Treatment
- Duplicate Record Detection
- Whitespace Removal
- Text Standardization
- Data Consistency Checks

## 📅 Data Type Validation

- Date Conversion
- Numeric Field Validation
- Object Field Inspection

## 📊 Business Rule Validation

Verified the following business rule:

```text
Total Price = Quantity × Unit Price
```

- Generated an `Expected_Total` validation column
- Detected mismatched records

## 📈 Outlier Detection

- Interquartile Range (IQR) Method
- Identification of unusual values

## 📤 Dataset Export

- Exported cleaned dataset
- Prepared dataset for EDA and visualization

---

# 📊 Dataset Summary

| Description | Value |
|-------------|------:|
| Total Records | **1,200** |
| Total Features | **14** |
| Missing Coupon Codes | **309** |
| Duplicate Records | **0** |
| Cleaned Dataset | ✅ |

---

# 🔄 Project Workflow

```text
Raw Dataset
      │
      ▼
Import Dataset
      │
      ▼
Data Exploration
      │
      ▼
Missing Value Analysis
      │
      ▼
Duplicate Detection
      │
      ▼
Data Cleaning
      │
      ▼
Text Standardization
      │
      ▼
Data Type Validation
      │
      ▼
Business Rule Validation
      │
      ▼
Outlier Detection
      │
      ▼
Export Clean Dataset
```

---

# 🖼️ Project Workflow Diagram

<p align="center">
  <img src="Data cleaning workflow infographic.png" alt="Project Workflow" width="900"/>
</p>

---

# 📂 Project Structure

```text
Project 1_Data Cleaning/
│
├── Data/
│   ├── Raw Data/
│   │   └── Raw_Dataset_for_Data_Analytics.xlsx
│   │
│   └── Processed Data/
│       └── Cleaned_Dataset.xlsx
│
├── Data Cleaning.ipynb
├── requirements.txt
├── Repository.txt
├── README.md
└── Data cleaning workflow infographic.png
```

---

# 🛠️ Technologies Used

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📓 Jupyter Notebook
- 📊 Microsoft Excel
- 📂 OpenPyXL

---

# 🚀 Installation & Setup

## Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/data-cleaning-preprocessing-python.git
```

## Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

## Step 3: Launch Jupyter Notebook

```bash
jupyter notebook
```

## Step 4: Open the Notebook

Open:

```text
Data Cleaning.ipynb
```

Run all cells sequentially.

---

# 📊 Data Cleaning Tasks Performed

- ✔ Imported Excel dataset
- ✔ Explored dataset structure
- ✔ Checked data types
- ✔ Identified missing values
- ✔ Filled missing `CouponCode` values
- ✔ Removed extra whitespace
- ✔ Standardized text formatting
- ✔ Checked duplicate records
- ✔ Validated business rules
- ✔ Created `Expected_Total` validation column
- ✔ Detected outliers using the IQR Method
- ✔ Exported the cleaned dataset

---

# 📈 Sample Analysis

The notebook includes:

- 📌 Missing Value Summary
- 📌 Duplicate Analysis
- 📌 Data Validation
- 📌 Business Rule Verification
- 📌 Outlier Detection
- 📌 Final Dataset Inspection

---

# 📚 Learning Outcomes

This project demonstrates practical knowledge of:

- Data Cleaning
- Data Preprocessing
- Data Validation
- Python Programming
- Pandas
- NumPy
- Business Rule Validation
- Exploratory Data Analysis (EDA)
- Data Quality Assessment
- Real-world Dataset Preparation

---

# 💼 Internship Information

**Internship:** Data Analytics Internship

**Organization:** DecodeLabs

---

# 📄 Requirements

```text
pandas
numpy
openpyxl
jupyter
```

---

# 📜 License

This project was developed for educational and portfolio purposes as part of my Data Analytics learning journey.

---

# 👨‍💻 Author

## Shakeel Ahmad

- 🎓 Software Engineering Student
- 📊 Aspiring Data Analyst
- 💻 Python | SQL | Pandas | Data Analytics Enthusiast

---

## ⭐ Support

If you found this project helpful, please consider giving it a **⭐ Star**.

Feedback, suggestions, and contributions are always welcome!

Let's connect and discuss **Python, Data Analytics, Pandas, SQL, Machine Learning, and Data Science.**

---

## 🔖 Topics

`Python` `Pandas` `NumPy` `Jupyter Notebook` `Data Cleaning` `Data Preprocessing` `Data Analytics` `EDA` `Excel` `OpenPyXL` `GitHub` `Portfolio` `DecodeLabs`
````
