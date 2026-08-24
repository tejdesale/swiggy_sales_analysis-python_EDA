<p align="center">
  <img src="https://raw.githubusercontent.com/tejdesale/swiggy_sales_analysis-python_EDA/main/Swiggy_OG.avif" alt="Swiggy Sales Analysis" width="100%">
</p>

<h1 align="center">🍴 Swiggy Sales Analysis - Python EDA</h1>

<p align="center">
  An end-to-end Exploratory Data Analysis of Swiggy order data using <b>Python, Pandas, Matplotlib, and Plotly</b>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-EDA-150458?logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Plotly-Interactive%20Charts-3F4F75?logo=plotly&logoColor=white">
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-F9AB00?logo=googlecolab&logoColor=white">
</p>

---

## 📌 Overview

This project analyzes **197,430 Swiggy food orders** across India to uncover key business insights - revenue trends, top-performing states and cities, customer ratings, and order patterns over time. The goal is to simulate a real-world **food delivery analytics workflow**, from raw data to actionable KPIs and visualizations.

---

## 📊 Dataset

| Column | Description |
|---|---|
| `State` | State where the order was placed |
| `City` | City where the order was placed |
| `Order Date` | Date the order was placed |
| `Restaurant Name` | Name of the restaurant |
| `Location` | Locality within the city |
| `Category` | Dish category (Snack, Momos, Recommended, etc.) |
| `Dish Name` | Name of the ordered dish |
| `Price (INR)` | Order price in Indian Rupees |
| `Rating` | Restaurant rating |
| `Rating Count` | Number of ratings received |

**Rows:** 197,430 &nbsp;•&nbsp; **Columns:** 10 &nbsp;•&nbsp; **Time Period:** Jan 2025 - Aug 2025

---

## 🎯 Key KPIs

| Metric | Value |
|---|---|
| 💰 Total Sales | ₹5,30,12,505.77 |
| ⭐ Average Rating | 4.34 |
| 🛒 Average Order Value | ₹268.51 |
| 👍 Total Ratings Count | 55,91,574 |
| 📦 Total Orders | 197,430 |

---

## 📈 Visualizations & Insights

This project includes the following charts, all built with **Matplotlib** and **Plotly** (styled in Swiggy's brand orange `#FC8019`):

- **Monthly Revenue Trend** - Line chart of sales across months
- **Daily Revenue Trend** - Sales distribution across days of the week
- **Veg vs Non-Veg Revenue Split** - Donut chart comparing food category contribution
- **Revenue by State** - Horizontal bar chart ranking all states by total sales
- **Quarterly Performance Summary** - Total sales, average rating, and order volume per quarter
- **Top 5 Cities by Sales** - Highest revenue-generating cities

### Sample Insight Highlights
- 🏆 **Karnataka** leads state-wise revenue, driven largely by **Bengaluru**
- 🥦 **Veg orders** contribute a significantly larger share of revenue than Non-Veg
- 📅 Sales stayed fairly consistent across Q1 and Q2 2025, with a dip in Q3
- ⭐ Average customer rating remains stable at **~4.34** across all quarters

---

## 🛠️ Tech Stack

- **Python 3.10**
- **Pandas** & **NumPy** - data cleaning and aggregation
- **Matplotlib** & **Seaborn** - static visualizations
- **Plotly Express** - interactive charts
- **Google Colab** - development environment

---

## 📁 Project Structure

```
swiggy_sales_analysis-python_EDA/
│
├── swiggy_sales_analysis.ipynb   # Main analysis notebook
├── swiggy_data.xlsx              # Raw dataset
├── 391398-swiggy.avif            # Cover image
└── README.md                     # Project documentation
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/tejdesale/swiggy_sales_analysis-python_EDA.git
   cd swiggy_sales_analysis-python_EDA
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn plotly openpyxl
   ```

3. **Run the notebook**
   - Open `swiggy_sales_analysis.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab
   - Run all cells to reproduce the analysis and visualizations

---

## 🔮 Future Improvements

- Add cuisine-level and dish-level revenue breakdowns
- Build an interactive dashboard (Streamlit / Power BI)
- Incorporate delivery time and customer segmentation analysis
- Add year-over-year comparisons once more historical data is available

---

## 🙌 Acknowledgements

Dataset curated for educational/portfolio purposes to demonstrate data analysis and visualization skills using real-world-style food delivery data.

---

<p align="center">Made with ❤️ and Python</p>
