# 🛒 Sales Data EDA Project

A complete **Exploratory Data Analysis (EDA)** project on a synthetic retail sales dataset. The project covers data generation, analysis, and visualization across key business dimensions like revenue, profit, region, and customer segments.

---

## 📁 Project Structure

```
├── data_generator.py       # Script to generate the synthetic sales dataset
├── sales_dataset.csv       # Generated dataset (1000 orders)
├── eda_analysis_summary.csv # Summary statistics from EDA
├── sales_chart.html        # Interactive sales visualizations
└── suman.ipynb             # Main Jupyter Notebook with full EDA
```

---

## 📊 Dataset Overview

The dataset is synthetically generated using **Faker** and **NumPy**, simulating a real-world retail business with 1000 orders across multiple categories, regions, and customer segments.

| Feature           | Details                                          |
| ----------------- | ------------------------------------------------ |
| Total Records     | 1,000 orders                                     |
| Date Range        | Last 2 years                                     |
| Categories        | Furniture, Office Supplies, Electronics, Grocery |
| Regions           | North, South, East, West                         |
| Payment Modes     | Cash, Credit Card, UPI, Net Banking              |
| Delivery Statuses | Delivered, Pending, Returned, Cancelled          |
| Customer Segments | Consumer, Corporate, Home Office                 |

### Columns

- `Order ID`, `Order Date`, `Ship Date`
- `Customer ID`, `Customer Name`, `Customer Segment`
- `Product ID`, `Product Name`, `Category`
- `Region`, `State`, `City`
- `Quantity`, `Unit Price`, `Discount (%)`, `Sales Amount`, `Cost Price`, `Profit`
- `Payment Mode`, `Delivery Status`
- `Supplier Name`, `Supplier Email`
- `Stock Left`, `Auto Reorder`, `Reorder Quantity`

---

## 📈 Key Insights

| Metric               | Value           |
| -------------------- | --------------- |
| 💰 Total Sales       | ₹1,31,22,188.65 |
| 📦 Total Orders      | 1,000           |
| 📊 Total Profit      | ₹32,93,592.57   |
| 📉 Avg Profit Margin | 25.10%          |
| 🏆 Top Category      | Furniture       |
| 🌍 Best Region       | East            |
| 👤 Best Segment      | Consumer        |

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy faker
```

### Generate the Dataset

```bash
python data_generator.py
```

This will create `sales_dataset.csv` with 1000 synthetic sales records.

### Run the EDA Notebook

```bash
jupyter notebook suman.ipynb
```

### View Interactive Charts

Open `sales_chart.html` in any browser to explore the interactive sales visualizations.

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Faker** – Synthetic data generation
- **Jupyter Notebook** – EDA and analysis
- **Plotly / HTML** – Interactive charts

---

## 📌 Project Highlights

- ✅ Fully synthetic dataset — no real customer data
- ✅ Auto reorder logic based on stock levels
- ✅ Profit margin calculation per order
- ✅ Multi-dimensional analysis (region, category, segment, payment)
- ✅ Interactive HTML dashboard

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
