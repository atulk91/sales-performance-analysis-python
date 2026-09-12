# Sales Performance Analysis

## Project Overview

This project analyzes agricultural sales transactions to identify revenue trends, product performance, city-wise performance, and month-on-month sales growth.

## Business Objective

The objective is to analyze sales data and identify top-performing products, cities, categories, and monthly business trends to support data-driven decisions.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Excel
- Jupyter Notebook

## Dataset

The dataset contains 1,000 agricultural sales transactions from January 2025 to May 2026.

### Main Columns

- Date
- Product
- Category
- Qty
- Rate
- Sales_Amount
- City

## Data Quality Checks

- No missing values found
- No exact duplicate records found
- No zero or negative quantity/rate values found
- Sales Amount was validated against `Quantity × Rate`
- All 1,000 transaction records matched successfully

## Analysis Performed

- Overall sales KPI analysis
- Product-wise sales and quantity analysis
- City-wise revenue and transaction analysis
- Category-wise performance analysis
- Monthly sales trend analysis
- Month-on-Month sales growth analysis
- Revenue contribution and ranking analysis
- Order-size categorization

## Key Insights

- Total sales revenue was approximately ₹2.03 crore.
- Pesticide was the top-performing product, generating ₹46.72 lakh and contributing 23% of total sales.
- Urea recorded the lowest product revenue at ₹35.54 lakh.
- Varanasi was the highest-revenue city at approximately ₹46.2 lakh.
- Deoria was the lowest-revenue city at approximately ₹36.7 lakh.
- November 2025 recorded the strongest Month-on-Month growth of 50.39%.
- May 2026 recorded the largest Month-on-Month decline of 70.09%.

## Business Recommendations

1. Study Varanasi's product mix and sales approach for possible adoption in Deoria.
2. Review Urea performance by city and month to identify demand, pricing, or availability issues.
3. Investigate the sharp sales decline in May 2026, including whether it represents a complete reporting month.
4. Monitor monthly sales growth to identify declining performance early.

## Visualizations

### City-wise Sales Revenue

![City-wise Sales Revenue](images/city_wise_sales_revenue.png)

### Product-wise Sales Revenue

![Product-wise Sales Revenue](images/product_wise_sales_revenue.png)

### Month-on-Month Sales Growth

![MoM Sales Growth](images/mom_sales_growth.png)

## Project Structure

```text
sales_analysis_project/
│
├── Data/
│   └── Sales Analysis Data set.xlsx
├── images/
│   ├── city_wise_sales_revenue.png
│   ├── product_wise_sales_revenue.png
│   └── mom_sales_growth.png
├── Notebooks/
│   └── Sales_Performance_Analysis.ipynb
└── README.md
```

## How to Run

1. Clone the repository.
2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

3. Open `Notebooks/Sales_Performance_Analysis.ipynb`.
4. Run all cells.