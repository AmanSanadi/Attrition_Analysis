# 📊 Strategic Workforce Attrition Analysis

> A data analysis project exploring employee attrition patterns across departments, job roles, salary bands, and time — built to help organisations understand *why* employees leave and *where* turnover is most concentrated.

This project consolidates five interconnected HR datasets into a unified, analysis-ready structure, applies thorough data cleaning and validation, and produces visual summaries of key workforce metrics. It is designed to demonstrate end-to-end data analysis skills suitable for People Analytics and HR Intelligence use cases.

---

## 🗂️ Datasets

| File | Description |
|---|---|
| `Employee.csv` | Core employee records — roles, departments, salary, performance |
| `Department.csv` | Department details, regional locations, and budget allocations |
| `Manager.csv` | Manager profiles, hire dates, and performance ratings |
| `Salary.csv` | Salary history, effective dates, and change reasons |
| `Attrition_date.csv` | Exit event records, attrition reasons, and exit interview scores |

---

## 🎯 Project Objectives

- Consolidate and clean data across five related HR datasets
- Resolve data quality issues — duplicates, invalid identifiers, inconsistent formats, and missing values
- Verify referential integrity across all tables
- Analyse attrition by job role, department, salary level, and time period
- Examine exit interview scores in relation to departure reasons
- Produce clear visualisations of twelve key workforce metrics

---

## 📈 Visualisations Included

`Gender Distribution` · `Employees by Job Role` · `Average Salary by Role` · `Attrition Distribution` · `Attrition Count` · `Attrition by Job Role` · `Attrition Trend Over Time` · `Employees by Department` · `Performance Rating Distribution` · `Attrition Reason Distribution`

---

## 🛠️ Prerequisites

- **Python** 3.8 or higher
- **Jupyter Notebook** or **JupyterLab**
- Raw data CSV files placed in the path referenced within the notebook

---

## 📦 Required Libraries

```bash
pip install pandas numpy matplotlib word2number
```

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, and transformation |
| `numpy` | Numerical operations and missing value handling |
| `matplotlib` | Chart and visualisation generation |
| `word2number` | Converting word-format salary values to numeric |

---

## 🚀 Getting Started

**1. Clone the repository**
```bash
git clone https://github.com/your-username/workforce-attrition-analysis.git
cd workforce-attrition-analysis
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Add your data files**

Place the five CSV files into your local data directory and update the file paths in the notebook accordingly.

**4. Launch the notebook**
```bash
jupyter notebook Employee_Attrition_Analysis.ipynb
```

**5. Run all cells**

Use `Kernel → Restart & Run All` to execute the full analysis from start to finish.


## 🧰 Built With

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 👤 Author

**Aman Sanadi**

---

<p align="center">
  <sub>Made with ♥ as part of a data analytics portfolio project</sub>
</p>
