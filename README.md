# Pandas Q4 2024 Sales Data Analysis

## Project Overview
This project focuses on cleaning and analyzing a messy Q4 2024 e-commerce sales dataset using Python and Pandas.

The dataset contains missing values and requires preprocessing before generating meaningful business insights.

---

## Dataset Columns

- transaction_id
- date
- region
- product_category
- sales_amount
- quantity
- customer_age
- payment_method

---

## Task 1: Data Inspection

- Loaded dataset using Pandas
- Used `df.info()` to inspect structure
- Used `df.isna().sum()` to detect missing values

---

## Task 2: Data Cleaning

Applied appropriate cleaning strategies:

- Filled `region` and `product_category` with mode
- Filled `sales_amount` with median
- Forward-filled `quantity`
- Filled `customer_age` with rounded mean
- Dropped rows with missing `payment_method`
- Verified no missing values remain

---

## Task 3: GroupBy Analysis

Performed aggregations:

- Total sales by region
- Average sales by product category
- Sales and quantity by region & product category
- Top 3 performing region-product combinations

---

## Task 4: Custom Aggregation

- Created `sales_range()` function (max - min)
- Calculated sales range per region
- Used `.agg()` to compute:
  - sales_amount → sum, mean, max
  - quantity → sum, min

---

## Key Insights

- Identified highest revenue generating region
- Determined best performing product categories
- Analyzed regional sales variability
- Cleaned dataset for reliable analysis

---

## Technologies Used

- Python
- Pandas
- Google Colab

---

## How to Run

1. Open the notebook in Google Colab
2. Run all cells
3. View outputs and analysis results

---

## Author

J-Harsha vardhan
