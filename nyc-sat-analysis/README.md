# 🧠 Exploring NYC Public School Test Result Scores

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-%3E%3D1.0-green)](https://pandas.pydata.org/)
[![SQLite](https://img.shields.io/badge/SQLite-Used-lightgrey)](https://www.sqlite.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)

---

## 📌 Project Overview

Standardized tests such as the SAT play a crucial role in shaping academic opportunities for high school students across the U.S.  
This project analyzes **New York City (NYC) public school SAT scores** to identify patterns of academic performance using **SQL queries in Python via SQLite and Pandas**.

Key SAT components analyzed include:

- **Math** (Max score: 800)
- **Reading** (Max score: 800)
- **Writing** (Max score: 800)

This project uses **SQL for querying** and **Pandas** for data processing and visualization, uncovering trends among high-performing schools and highlighting borough-based educational inequalities.

---

## 🎯 Objective

To analyze SAT scores from NYC public schools and uncover:

- Which schools score highest in SAT Math
- The top 10 schools based on total SAT scores
- Which borough has the greatest SAT score variation
- Borough-level performance gaps and trends

---

## 🛠️ Tools & Technologies

| Tool            | Purpose                                  |
|-----------------|-------------------------------------------|
| `Python 3.11`   | Core programming language                 |
| `Pandas`        | Data cleaning & transformation            |
| `SQLite`        | Executing SQL queries on local database   |
| `ipython-sql`   | Writing SQL directly in Jupyter Notebook  |
| `Matplotlib`    | Creating visuals to communicate insights  |
| `Jupyter Lab`   | Interactive data exploration              |

---

## 📈 Key Findings

### 📊 Best Math Results
- Schools with average math scores above **640** (80% of max 800) are top performers.
- These schools excel in quantitative skills.


### 🥇 Top 10 Total SAT Scores
- Ranked by combined Math + Reading + Writing scores.
- Top 10 schools show balanced academic excellence.
![top 10_total_SAT Scores](assets/top10_SAT_scores.jpg.jpg)

### 🗽 Borough with Highest SAT Score Variation
- One borough shows the largest performance spread.
- Highlights inequalities and potential focus areas.
  ![Borough with Highest SAT Score Variation](assets/SAT_scores.jpg)
