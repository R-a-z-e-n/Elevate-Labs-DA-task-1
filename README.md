# Elevate-Labs-DA-task-1

# 🧹 Data Cleaning Pipeline: Excel / Python (Pandas)

## 📌 Objective
Clean and prepare a raw dataset by handling missing values, duplicates, inconsistent formats, and data types using Python (Pandas) or Excel.

## 🛠 Tools
- Python (Google Colab or Jupyter Notebook)
- Pandas library
- Excel (optional for manual inspection)

## 📂 Input
- A raw `.csv` dataset uploaded via Google Colab

## 📤 Output
- A cleaned `.csv` dataset ready for analysis or modeling
- A printed summary of changes applied

---

## 🔍 Cleaning Steps

1. **Upload Dataset**
   - Use Google Colab’s file upload to load your `.csv` file

2. **Handle Missing Values**
   - Identify missing values using `.isnull()`
   - Drop or fill missing values (e.g., median for age)

3. **Remove Duplicates**
   - Use `.drop_duplicates()` to eliminate repeated rows

4. **Standardize Text**
   - Normalize values like gender (`male`, `female`) and country names (`India`, `USA`, etc.)

5. **Convert Date Formats**
   - Ensure all dates follow `dd-mm-yyyy` format using `pd.to_datetime()`

6. **Rename Columns**
   - Clean column headers: lowercase, no spaces, underscores instead

7. **Fix Data Types**
   - Convert columns like `age` to integer, `dob` to datetime

8. **Export Cleaned Dataset**
   - Save and download the cleaned dataset as `cleaned_dataset.csv`

9. **Print Summary**
   - Display final shape, column names, and data types

---

## 🚀 How to Run (Google Colab)

1. Open [Google Colab](https://colab.research.google.com)
2. Copy and paste the Python script from this repo
3. Run each cell step by step
4. Upload your `.csv` file when prompted
5. Download the cleaned dataset

---

## 📈 Example Use Cases
- Preparing survey data for analysis
- Cleaning e-commerce transaction logs
- Standardizing HR or CRM datasets

---

## 📄 License
MIT License — free to use, modify, and distribute

---


Hyderabad, India

