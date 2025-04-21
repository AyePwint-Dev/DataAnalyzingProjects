# DataAnalyzingProjects
# 📊 Exploring NYC Public School Test Result Scores

This project analyzes SAT performance across NYC public high schools using Python and pandas.

## 🔍 Objectives

1. **Identify top math-performing schools**
2. **Find the top 10 schools based on total SAT scores**
3. **Determine which borough shows the most variability in SAT performance**

---

## 📈 Best Math Results

- We define **"best math results"** as schools scoring at least **80% of the maximum possible SAT math score (800)**.
- Results are stored in a pandas DataFrame named **`best_math_schools`**, including:
  - `school_name`
  - `average_math`
- The results are **sorted in descending order** by `average_math`.

---

## 🏅 Top 10 Schools by Total SAT Score

- A new column **`total_SAT`** is created by summing the math, reading, and writing scores.
- The top 10 performing schools are stored in a DataFrame called **`top_10_schools`**, containing:
  - `school_name`
  - `total_SAT`
- Sorted by `total_SAT` in **descending order**.

---

## 🏙️ Borough with Largest SAT Score Standard Deviation

- We compute SAT score variability by borough.
- The borough with the **highest standard deviation** of `total_SAT` is saved in **`largest_std_dev`**, including:
  - `borough`
  - `num_schools` (number of schools in the borough)
  - `average_SAT` (mean total SAT score)
  - `std_SAT` (standard deviation of total SAT score)
- All numeric values are **rounded to two decimal places**.

---

## 🛠️ Tools Used

- Python 🐍
- pandas 🐼
- Jupyter Notebook 📓

---

## ✅ Status

Project completed and results stored in respective pandas DataFrames:
- `best_math_schools`
- `top_10_schools`
- `largest_std_dev`

---

Feel free to explore and build upon this analysis!
