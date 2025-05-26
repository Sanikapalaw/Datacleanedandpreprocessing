# Task 1: Data Cleaning and Preprocessing

## 📌 Objective
Clean and prepare a raw dataset by handling missing values, removing duplicates, standardizing text formats, converting data types, and making the data ready for analysis or modeling.

---

## 🗂 Dataset Used
**Marketing Campaign Dataset** (Kaggle)  
Link: [https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign)

---

## 🔧 Tools Used
- Python 🐍
- Pandas 📊
- Jupyter Notebook / Google Colab

---

## 🧹 Cleaning Steps Performed

1. **Loaded Dataset** using Pandas.
2. **Explored the Data** using `.head()`, `.info()`, `.describe()`.
3. **Checked for Missing Values** using `.isnull().sum()`:
   - Found 24 missing values in the `Income` column.
   - Filled missing `Income` values with the median.
4. **Removed Duplicate Rows** using `.drop_duplicates()`.
5. **Standardized Text Columns**:
   - Converted all object/text columns to lowercase and removed extra spaces.
6. **Renamed Column Headers**:
   - Changed column names to lowercase and replaced spaces with underscores for consistency.
7. **Converted Date Column**:
   - Converted `Dt_Customer` to datetime format.
8. **Checked and Fixed Data Types**:
   - Ensured `Year_Birth` is of type `int`.

---

## ✅ Final Output

- ✅ No missing values
- ✅ No duplicate rows
- ✅ Clean, uniform column names
- ✅ Consistent date and numeric formats

---

## 📁 Files Included

- `cleaning_script.ipynb` — Python code for cleaning
- `marketing_campaign_cleaned.csv` — Cleaned dataset
- `README.md` — Task explanation and summary

---

## 💡 Learnings

- How to handle missing values using `fillna()` and `median`.
- How to remove duplicates with `drop_duplicates()`.
- How to standardize and clean text data.
- Importance of data type conversion and column naming conventions.
- Prepared a ready-to-use dataset for future analysis or modeling tasks.

---

## 📬 Contact

Feel free to connect with me on [LinkedIn](https://linkedin.com/in/sanika-palaw-7583a3289) if you have any questions or feedback!

