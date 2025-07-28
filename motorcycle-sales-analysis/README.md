# 🏍️ Motorcycle Parts Wholesale Revenue Analysis

## 📘 Project Overview

This project analyzes wholesale sales data from a motorcycle parts retailer operating three warehouses (North, Central, and West) over a 3-month period: **June to August**. The goal is to uncover:

- Revenue trends by product line
- Seasonal sales variation
- Warehouse performance insights

The board wanted to optimize inventory and better understand where revenue is concentrated across their wholesale business.

---

## 🛠️ Tools & Technologies

- **SQL (SQLite)** – for data filtering, aggregation, and transformation
- **Pandas** – for DataFrame manipulation and integration with SQL
- **Seaborn & Matplotlib** – for building visualizations
- **Jupyter Notebook** – for end-to-end analysis and storytelling

---

## 📊 Key Results

- 📦 **Central warehouse** outperformed all others in total revenue across all months
- 🔧 **Braking systems** and **engine parts** were the top-performing product lines
- 📉 **August** saw dips in multiple categories — possibly seasonal or supply-related
- 📈 **July** was the strongest month overall for wholesale performance

---

## ✅ Business Recommendations

- Focus on **top-performing product lines** in underperforming warehouses
- Reevaluate inventory levels and demand forecasting for August
- Continue scaling operations at the Central warehouse
- Consider seasonal marketing campaigns for July

---

## 📈 Visualizations

The notebook includes:

- 📊 **Bar chart**: Revenue by warehouse and month
- 📈 **Line chart**: Product line performance trends
- 🧩 **Pie chart**: Revenue share by product line
- 🔥 **Heatmap**: Monthly product performance

Each chart is followed by Markdown insights summarizing key takeaways.

---

## 💻 How to Run This Project

1. Clone this repository or download the files
2. Open the notebook `motorcycle-sales-analysis.ipynb` using Jupyter
3. Run the cells sequentially
4. (Optional) Install packages with:

```bash
pip install pandas matplotlib seaborn sqlalchemy ipython-sql
