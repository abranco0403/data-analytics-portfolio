# 🎬 Netflix 90s Movies EDA

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![SQLite](https://img.shields.io/badge/SQLite-Used-lightgrey)](https://www.sqlite.org/)
[![Pandas](https://img.shields.io/badge/Pandas-%3E%3D1.0-green)](https://pandas.pydata.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)

---

## 📌 Project Overview

Netflix has evolved from a DVD rental company into one of the world's largest streaming platforms. This project dives into the **Netflix movie catalog from the 1990s**, analyzing patterns across genres, durations, countries, and directors.

This analysis simulates the perspective of a **production company focused on nostalgic content**, aiming to understand what made 90s movies distinct and which titles or creators stand out.

The analysis is conducted using **pure SQL inside Jupyter**, with Python used only for setup and minimal visualization.

---

## 🎯 Objective

To explore Netflix’s 1990s movie catalog and uncover:

- The most common movie duration
- How many short action movies (< 90 min) were released
- Which genres and countries dominated the 90s catalog
- Who were the most prolific directors
- How 90s movies were added to Netflix over time

---

## 🛠️ Tools & Technologies

| Tool            | Purpose                                       |
|-----------------|------------------------------------------------|
| `Python 3.11`   | Basic setup and data loading                  |
| `SQLite`        | SQL-based data analysis                       |
| `ipython-sql`   | Writing and executing SQL directly in Jupyter |
| `Pandas`        | Displaying SQL results and basic I/O          |
| `Matplotlib`    | Simple visual summaries of results            |
| `Jupyter Lab`   | Notebook interface for clean storytelling     |

---

## 📈 Key Insights

### ⏱️ Most Common Duration
- The most frequent runtime for movies in the 1990s was **`90 minutes`**, showing a preference for tight, standard-length storytelling.

### 🎬 Short Action Movies
- The 1990s saw **`X` short action movies** (less than 90 minutes) in the catalog — ideal for fast-paced, high-impact storytelling.

### 🌍 Top Countries
- Countries like the **United States**, **India**, and **France** led in production volume for 90s content on Netflix.

### 🎭 Top 5 Genres
- Most popular 1990s genres (by count):
  1. Dramas
  2. Action & Adventure
  3. Comedies
  4. Thrillers
  5. Horror Movies

![Top Genres](assets/top5_genres_90s_netflix)

### 🎥 Most Prolific Directors
- Several directors contributed **multiple titles** during the 1990s, showing consistency in output across that decade.

### 📅 Year Added Trend
- Many 90s movies were added to Netflix between **2016–2020**, aligning with the company’s growing interest in nostalgic content.

---

## 📂 Folder Structure

