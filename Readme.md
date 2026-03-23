# 🛒✨ Sales Data EDA Project

> 🚀 A complete **Exploratory Data Analysis (EDA)** project built on a synthetic retail dataset — covering **data generation, business insights, and interactive visualization**.

---

## 🌟 Overview

This project simulates a **real-world retail business** using synthetic data and performs deep analysis to uncover:

* 💰 Revenue trends
* 📈 Profit insights
* 🌍 Regional performance
* 👥 Customer behavior

---

## 📁 Project Structure

```
📦 EDA-Data-Analysis
├── 🧠 data_generator.py        # Generate synthetic dataset
├── 📊 sales_dataset.csv        # Raw dataset (1000 records)
├── 📑 eda_analysis_summary.csv # Processed EDA insights
├── 🌐 sales_chart.html         # Interactive dashboard
└── 📓 suman.ipynb              # Full analysis notebook
```

---

## 📊 Dataset Overview

✨ Generated using **Faker + NumPy** to mimic real business scenarios

| 🔑 Feature         | 📌 Details                                       |
| ------------------ | ------------------------------------------------ |
| 📦 Total Records   | 1,000 orders                                     |
| 📅 Date Range      | Last 2 years                                     |
| 🛍️ Categories     | Furniture, Office Supplies, Electronics, Grocery |
| 🌍 Regions         | North, South, East, West                         |
| 💳 Payment Modes   | Cash, Credit Card, UPI, Net Banking              |
| 🚚 Delivery Status | Delivered, Pending, Returned, Cancelled          |
| 👤 Segments        | Consumer, Corporate, Home Office                 |

---

## 🧾 Columns Included

* 📌 Order & Shipping → `Order ID`, `Order Date`, `Ship Date`
* 👤 Customer Info → `Customer ID`, `Customer Name`, `Segment`
* 🛍️ Product Info → `Product ID`, `Product Name`, `Category`
* 🌍 Location → `Region`, `State`, `City`
* 💰 Sales Metrics → `Quantity`, `Unit Price`, `Discount`, `Sales`, `Profit`
* 🚚 Logistics → `Delivery Status`, `Payment Mode`
* 📦 Inventory → `Stock Left`, `Auto Reorder`, `Reorder Quantity`

---

## 📈 Key Insights

| 📊 Metric            | 💡 Value        |
| -------------------- | --------------- |
| 💰 **Total Sales**   | ₹1,31,22,188.65 |
| 📦 **Total Orders**  | 1,000           |
| 📊 **Total Profit**  | ₹32,93,592.57   |
| 📉 **Profit Margin** | 25.10%          |
| 🏆 **Top Category**  | Furniture       |
| 🌍 **Best Region**   | East            |
| 👤 **Best Segment**  | Consumer        |

---

## 🚀 Getting Started

### ⚙️ Install Dependencies

```bash
pip install pandas numpy faker
```

---

### 🧪 Generate Dataset

```bash
python data_generator.py
```

📁 Output → `sales_dataset.csv`

---

### 📊 Run Analysis

```bash
jupyter notebook suman.ipynb
```

---

### 🌐 View Dashboard

👉 Open in browser:

```
sales_chart.html
```

---

## 🛠️ Tech Stack

* 🐍 **Python 3.x**
* 📊 **Pandas** – Data Analysis
* 🔢 **NumPy** – Numerical Ops
* 🎭 **Faker** – Fake Data Generation
* 📓 **Jupyter Notebook** – Analysis
* 🌐 **Plotly + HTML** – Interactive Dashboard

---

## ✨ Project Highlights

* ✅ 100% Synthetic Data (Safe & Shareable)
* ✅ Realistic Business Simulation
* ✅ Auto Reorder Inventory Logic
* ✅ Profit Margin Analysis
* ✅ Multi-Dimensional Insights
* ✅ Interactive Visual Dashboard

---

## 🤝 Contributing

💡 Contributions are welcome!

1. Fork the repo 🍴
2. Create a new branch 🌱
3. Make changes ✨
4. Submit a PR 🚀

---

## 📄 License

📜 Licensed under the **MIT License**

---

## ⭐ Support

If you like this project:
👉 Give it a **⭐ on GitHub**
👉 Share with others 🚀

---

### 💬 Author

👨‍💻 **Suman Jhanp**
📊 Aspiring Data Analyst | Python | EDA | Visualization

---
