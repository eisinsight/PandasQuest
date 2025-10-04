
# 🐼 PandasQuest: Mastering DataFrame Operations in Python

**PandasQuest** is a curated collection of essential pandas techniques for data cleaning, transformation, and exploration. Designed for analysts, engineers, and strategists, this repository showcases modular, real-world examples that accelerate your journey from raw data to executive-ready insights.

## 📦 Features Covered

### 🔍 Data Inspection
- `df.info()` – Overview of structure, types, and memory usage
- `df.describe()` – Summary statistics for numeric columns
- `df.head()`, `df.tail()` – Quick data previews

### 🧼 Data Cleaning
- Handling nulls: `df.isnull()`, `df.fillna()`, `df.dropna()`
- Detecting duplicates: `df.duplicated()`
- Removing duplicates: `df.drop_duplicates()`

### 🧠 Column Operations
- Creating new columns: `df['new_col'] = ...`
- Column-wise mean: `df['col'].mean()`

### 🧮 Aggregation & Grouping
- `df.groupby('key').mean()` – Grouped statistics

### 🔄 Reshaping Data
- `df.pivot(index, columns, values)` – Pivoting for wide-format views

### 🔗 Merging & Joining
- `pd.merge(df1, df2, on='key', how='inner')` – SQL-style joins

## 🧠 Author

Crafted by **Muhammad Eis**, Data Strategist , specializing in branded, cinematic data storytelling for executive audiences.

