# Sales Analytics & Forecasting Project

end-to-end data analysis project that explore 4 years of sales data to extract business insights and forcast future revenue.  

**Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, SQL, Scikit-learn, Power BI

---

## Project Structure
sales-analytics-project/
│
├── data/
│   └── superstore.csv
│
├── notebooks/
│   ├── 01_cleaning_exploration.ipynb
│   ├── 02_sql_analysis.ipynb
│   └── 03_forecasting_model.ipynb
│
├── dashboard/
│   └── sales_dashboard.pbix
│
└── README.md
│
└── requirements.txt

---

## Notebooks

### 01 — Data Cleaning & Exploration - Key Findings
#### Missing Values
No missing values found across all 21 columns. Dataset is complete and ready for analysis.

#### Negative Profit Investigation
- A portion of orders have negative profit, meaning the company is losing money on them
- **Root Cause:** Excessive discounting — orders with higher discounts consistently fall below break-even
- **Most loss-making sub-category: Binders**
  - Binders had the highest total losses across all sub-categories
  - High average discount rate is the primary driver of these losses
  - Clear pattern observed: as discount increases, profit drops below zero

#### Business Recommendation
The company should review its discounting strategy for Binders specifically,
and set a maximum discount threshold to avoid selling below cost.

---
## Dataset

- **Source:** [Superstore Dataset - Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Size:** 9,994 rows, 21 columns
- **Period:** 2014 – 2017

---
## How to Run

1. Clone the repo
```bash
   git clone https://github.com/your-username/sales-analytics-project.git
```
2. Install dependencies
```bash
   pip install -r requirements.txt
```
3. Open any notebook in VS Code or Jupyter and run cells sequentially
