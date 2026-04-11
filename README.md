# Sales Analytics & Forecasting Project

End-to-end data analysis project exploring 4 years of retail sales data
to extract business insights and forecast future revenue.

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, SQL, Scikit-learn, Power BI

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
├── README.md
└── requirements.txt

---

## Dataset
- **Source:** [Superstore Dataset - Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Size:** 9,994 rows, 21 columns
- **Period:** 2014 – 2017

---

## Key Findings
### Notebook 1 - Data Exploration
- Technology leads in both sales and profit margin (17.40%)
- Furniture generates high revenue but only 2.49% margin — severely impacted by discounting
- Central region is the least efficient with 7.92% profit margin vs West at 14.94%
- Binders are the most loss-making sub-category due to excessive discounts
- Sales show consistent YoY growth with predictable seasonal dips in January 
  and peaks in November/December

### Notebook 2 - SQL Analysis
- Top 10 profitable products are all Technology items led by Canon imageCLASS at 40.9% margin
- Bottom 10 loss-making products are dominated by Furniture and mispriced Technology items
- Home Office segment has the highest profit margin (14.03%) 
  despite being the smallest segment by order volume
- Top customers are concentrated in West and East regions
- Tamara Chand is the single most valuable customer at 47% profit margin
- Discount above 20% guarantees a loss — identified as the root cause 
  of all profitability issues across categories, products and regions

## How to Run
1. Clone the repo
```bash
   git clone https://github.com/your-username/sales-analytics-project.git
```
2. Install dependencies
```bash
   pip install -r requirements.txt
```
3. Open any notebook in VS Code and run cells sequentially