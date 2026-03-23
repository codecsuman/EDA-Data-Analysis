# 🛒✨ Sales Data EDA Project

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-Vercel-black?style=for-the-badge&logo=vercel)](https://eda-data-analysis.vercel.app/)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)](https://pandas.pydata.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

> 🎯 A complete **Exploratory Data Analysis (EDA)** project on a synthetic retail sales dataset — covering data generation, analysis, and visualization across revenue, profit, region, and customer segments.

---

## 🌐 Live Dashboard

<div align="center">

### 👉 [**View Live on Vercel →**](https://eda-data-analysis.vercel.app/)

</div>

---

## ⚡ Quick Start — One Copy-Paste Command

```bash
git clone https://github.com/codecsuman/EDA-Data-Analysis.git && cd EDA-Data-Analysis && pip install pandas numpy faker jupyter plotly && python data_generator.py && jupyter notebook suman.ipynb
```

---

## 📁 Project Structure

```
EDA-Data-Analysis/
├── 🐍 data_generator.py        # Script to generate the synthetic sales dataset
├── 📊 sales_dataset.csv         # Generated dataset (1000 orders)
├── 📋 eda_analysis_summary.csv  # Summary statistics from EDA
├── 🌐 sales_chart.html          # Interactive sales visualizations
└── 📓 suman.ipynb               # Main Jupyter Notebook with full EDA
```

---

## 📊 Dataset Overview

The dataset is synthetically generated using **Faker** and **NumPy**, simulating a real-world retail business.

| 🔖 Feature | 📌 Details |
|---|---|
| 📦 Total Records | 1,000 orders |
| 📅 Date Range | Last 2 years |
| 🏷️ Categories | Furniture, Office Supplies, Electronics, Grocery |
| 🌍 Regions | North, South, East, West |
| 💳 Payment Modes | Cash, Credit Card, UPI, Net Banking |
| 🚚 Delivery Statuses | Delivered, Pending, Returned, Cancelled |
| 👤 Customer Segments | Consumer, Corporate, Home Office |

### 🗂️ Columns at a Glance

- 🆔 `Order ID`, `Order Date`, `Ship Date`
- 👤 `Customer ID`, `Customer Name`, `Customer Segment`
- 📦 `Product ID`, `Product Name`, `Category`
- 🌍 `Region`, `State`, `City`
- 💰 `Quantity`, `Unit Price`, `Discount (%)`, `Sales Amount`, `Cost Price`, `Profit`
- 💳 `Payment Mode`, `Delivery Status`
- 🏭 `Supplier Name`, `Supplier Email`
- 📦 `Stock Left`, `Auto Reorder`, `Reorder Quantity`

---

## 📈 Key Insights

| Metric | Value |
|---|---|
| 💰 Total Sales | ₹1,31,22,188.65 |
| 📦 Total Orders | 1,000 |
| 📊 Total Profit | ₹32,93,592.57 |
| 📉 Avg Profit Margin | 25.10% |
| 🏆 Top Category | Furniture |
| 🌍 Best Region | East |
| 👤 Best Segment | Consumer |

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

| Tool | Purpose |
|---|---|
| 🐍 Python 3.x | Core language |
| 🐼 Pandas | Data manipulation |
| 🔢 NumPy | Numerical operations |
| 🎭 Faker | Synthetic data generation |
| 📓 Jupyter Notebook | EDA and analysis |
| 📊 Plotly / HTML | Interactive charts |
| 🚀 Vercel | Deployment & hosting |

---

## 📌 Project Highlights

- ✅ Fully synthetic dataset — no real customer data
- ✅ Auto reorder logic based on stock levels
- ✅ Profit margin calculation per order
- ✅ Multi-dimensional analysis (region, category, segment, payment)
- ✅ Interactive HTML dashboard
- ✅ Deployed live on Vercel

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

Made with ❤️ by [codecsuman](https://github.com/codecsuman)

[![Live Demo](https://img.shields.io/badge/🚀%20View%20Live-eda--data--analysis.vercel.app-black?style=for-the-badge&logo=vercel)](https://eda-data-analysis.vercel.app/)

</div>
