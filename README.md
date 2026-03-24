# 🐼 Pandas Exercise

A hands-on collection of Jupyter Notebooks for learning and practicing **data manipulation with Python Pandas** — from the basics of DataFrames to advanced operations like GroupBy, Pivoting, and Merging.

---

## 📁 Project Structure

```
Pandas-Exercise/
│
├── DataFrames.ipynb                    # Creating DataFrames from dicts, CSV & Excel
├── Exploring Data in Pandas.ipynb      # head(), tail(), info(), describe(), isnull()
├── Column Transformations-Part1.ipynb  # Conditional column creation with .loc[]
├── Column Transformation Part-2.ipynb  # Custom functions with .map()
├── Handling Null Values.ipynb          # Detecting and dropping null values
├── Handling Duplicates.ipynb           # Finding and removing duplicate rows
├── GroupBy.ipynb                       # Aggregations with groupby()
├── Marge-Concatenate-Join.ipynb        # merge(), concat(), and join types
├── Pivot and Melting.ipynb             # pivot() and melt() for reshaping data
│
├── ESD.xlsx                            # Employee dataset (used in most notebooks)
├── Book1.xlsx                          # Month data for column transformation
├── expense3.xlsx                       # Expense records
├── Customers_Data.csv                  # Customer dataset
├── employees.csv                       # Employee CSV data
└── company1.csv                        # Company data with duplicates & nulls
```

---

## 📒 Notebooks Overview

| Notebook | Topics Covered |
|---|---|
| `DataFrames.ipynb` | Creating DataFrames, reading CSV & Excel files |
| `Exploring Data in Pandas.ipynb` | `head()`, `tail()`, `info()`, `describe()`, `isnull()` |
| `Column Transformations-Part1.ipynb` | Conditional columns using `.loc[]` |
| `Column Transformation Part-2.ipynb` | Custom transformations using `.map()` |
| `Handling Null Values.ipynb` | `isnull()`, `dropna()`, null value analysis |
| `Handling Duplicates.ipynb` | `duplicated()`, `drop_duplicates()` |
| `GroupBy.ipynb` | `groupby()` with `agg()` — count, mean, max |
| `Marge-Concatenate-Join.ipynb` | `merge()` with inner, left, right joins |
| `Pivot and Melting.ipynb` | `pivot()` and `melt()` for reshaping DataFrames |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed along with the required libraries:

```bash
pip install pandas openpyxl jupyter
```

### Run the Notebooks

```bash
git clone https://github.com/your-username/Pandas-Exercise.git
cd Pandas-Exercise
jupyter notebook
```

Then open any `.ipynb` file from the Jupyter interface in your browser.

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas**
- **Jupyter Notebook**
- **OpenPyXL** (for reading `.xlsx` files)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo, add more exercises or datasets, and open a pull request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

