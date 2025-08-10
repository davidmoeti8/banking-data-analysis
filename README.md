is

This project analyzes anonymized banking transaction and user datasets to uncover customer insights, spending patterns, and credit risk segments.

## Contents

- **Data Cleaning and Merging** using Python and DuckDB
- **Exploratory Data Analysis (EDA)** with SQL and visualizations in Python
- Insights on:
  - Customer segmentation
  - Credit scores
  - Merchant categories
  - Transaction times and states
- Optional: Refund and card brand analysis

## How to Run

1. Ensure you have Python 3.x installed.
2. Install dependencies:
   ```bash
   pip install duckdb pandas matplotlib seaborn
   ```
3. Place datasets in the `/data` folder or update file paths accordingly.
4. Run the notebook `banking_data_analysis.ipynb` step-by-step.

## Datasets

- `users_data_staging.csv`
- `transactions_full2.csv`

*Datasets are not included due to privacy. Please upload your own or get permission before use.*

## Insights

- Young adults carry higher debt and income levels.
- Poor credit scores correlate with higher debt.
- Grocery stores dominate transactions.
- California leads transaction volume.
- Morning is the busiest time for transactions.

## GitHub Repository

Explore the full project code, data analysis, and insights here:  
[https://github.com/davidmoeti8/banking-data-analysis](https://github.com/davidmoeti8/banking-data-analysis)

## License

This project is licensed under the MIT License - see the LICENSE file for details.
