# Retail Sales EDA

Exploratory Data Analysis of a retail sales dataset using Python.

## What this project covers

- Dataset inspection and data quality checks
- Descriptive statistics
- Monthly and quarterly sales trends
- Customer age-group and gender analysis
- Top 10 products by quantity sold
- Revenue by product category
- Correlation heatmap
- Regional sales analysis
- Business findings and recommendations

## Tools

- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

## Dataset

The analysis uses `retail_sales_data.csv`.

The dataset contains 6,500 rows and 16 columns, covering orders from January 2023 to December 2024.

## Main observations

- Total sales are approximately 28.01 million.
- Q4 is the strongest sales period in both years.
- The 25–34 age group has the highest sales contribution.
- Electronics is the highest-sales product category.
- South and West are the two largest regions by sales.
- Sales and Profit have a strong positive correlation, while Discount has a negative relationship with Profit in this dataset.

## Recommendations

1. Prepare inventory and promotions ahead of Q4.
2. Closely monitor the Electronics category because of its strong sales and profit contribution.
3. Build targeted campaigns around the 25–34 customer group.
4. Compare the South/West regions with Central to understand differences in demand and product mix.

## How to run

1. Clone or download this repository.
2. Install the required Python packages:
   `pip install -r requirements.txt`
3. Open `Retail_Sales_EDA.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the notebook from top to bottom.

## Project structure

text
Retail-Sales-EDA/
├── Retail_Sales_EDA.ipynb
├── retail_sales_data.csv
├── README.md
├── requirements.txt
└── Output/EDA_Summary.txt

