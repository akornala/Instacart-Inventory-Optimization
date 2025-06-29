# 🛒 Instacart Inventory Optimization

A data-driven project for inventory and sales optimization in a simulated supermarket chain (based on Instacart-like data).

**Want to know:**  
- 📈 Which products and departments are your best sellers?
- 📉 Where are the stockouts and overstock risks?
- 🔮 How can you forecast demand and optimize replenishment?

You’re in the right place!  
This project uses Python, pandas, forecasting models, and business analytics best practices—*real business analyst portfolio material*.

---

## 🤔 Why This Project?

Modern retailers need to:
- Forecast demand accurately (by SKU, brand, department)
- Minimize waste & lost sales from bad inventory decisions
- Identify cash cows and slow movers
- Optimize order quantities, turnover, and shelf space

This project walks through **real-life inventory optimization** using public supermarket sales data.

---

## 🚀 Features

| Feature               | Description                                                    |
|-----------------------|----------------------------------------------------------------|
| 📦 Data Cleaning      | Removes duplicates, handles missing values, standardizes types |
| 📊 Sales Analysis     | Trends by month, department, and product                       |
| 🔮 Demand Forecasting | Holt-Winters time series models for monthly sales prediction   |
| 📦 Inventory Modeling | EOQ, Reorder Point, and simulated replenishment                |
| 📈 Turnover Analysis  | ABC classification, fast/slow mover identification            |
| 📑 Ready for Dashboard| All results exported for visualization in Tableau or Power BI  |

---

## 🛠️ Built With

- Python 3.x
- pandas, numpy, matplotlib
- statsmodels (forecasting)
- [Kaggle supermarket dataset](https://www.kaggle.com/datasets/babsibz/supermarket-datasets)

---

## 📁 Project Structure

```bash
Instacart-Inventory-Optimization/
├── inventory_analysis.ipynb         # Main notebook
├── exports/                         # Processed CSVs for Tableau/dashboard
│   ├── department_sales.csv
│   ├── turnover_by_product.csv
│   ├── sales_actual_forecast_combined_clean.csv
│   └── ...
├── .gitignore
└── README.md
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/akornala/Instacart-Inventory-Optimization.git
   cd Instacart-Inventory-Optimization
   ```
2. **(Optional) Create and activate a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. **Open and run the notebook**

   * Launch Jupyter Notebook or VS Code.
   * Open `inventory_analysis.ipynb`.
   * Follow each section for data cleaning, analysis, forecasting, and result export.

---

## 🔑 Key Assumptions

* **No true inventory data:** Inventory on hand is inferred from order history and turnover models.
* **No expiry dates:** Turnover/spoilage is modeled via sales velocity, not actual product dates.
* **Forecasting is monthly:** Daily detail is not necessary for store-level decisions.
* **EOQ & ROP values:** Used standard retail assumptions for lead time, order cost, holding cost, etc.
* **Synthetic environment:** Data simulates a real retailer but is not from a live business.

---

## 📚 Data Source

* **Dataset:** [Kaggle - Supermarket Datasets (2015–2023)](https://www.kaggle.com/datasets/babsibz/supermarket-datasets)
* **Files Used:** `orders.csv`, `products.csv`, `departments.csv`, `aisle.csv`

---

## 🙋‍♂️ Author

**Akhil Kornala**
Business Analyst · Data Enthusiast
[LinkedIn](https://www.linkedin.com/in/akhilkornala/) · [GitHub](https://github.com/akornala)

---

## ⭐️ Show Your Support

If you find this project helpful:

* ⭐️ Star the repo
* 🛠️ Fork and build on it
* 🧠 Connect on [LinkedIn](https://www.linkedin.com/in/akhilkornala/)

---

## 📜 License

This project is open-source under the MIT License.

```