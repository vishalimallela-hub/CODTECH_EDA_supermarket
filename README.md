# Supermarket Sales - Exploratory Data Analysis

## Internship Details

- **Intern ID:** CITS8940
- **Full Name:** CITS8940
- **No. of Weeks:** YOUR_NUMBER_OF_WEEKS
- **Project Name:** Exploratory Data Analysis (EDA)

## Project Scope

This project focuses on performing Exploratory Data Analysis on a supermarket sales dataset to identify sales patterns, customer behavior, product performance, payment preferences, and relationships between numerical variables.

## Dataset

The project uses a public Supermarket Sales dataset containing 1000 transactions and 17 columns.

The dataset includes information such as:

- Invoice ID
- Branch
- City
- Customer Type
- Gender
- Product Line
- Unit Price
- Quantity
- Tax
- Total
- Date
- Time
- Payment
- Cost of Goods Sold (COGS)
- Gross Income
- Customer Rating

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. Imported the required Python libraries.
2. Loaded the supermarket sales dataset.
3. Inspected the dataset structure and columns.
4. Checked for missing values.
5. Checked for duplicate records.
6. Converted Date and Time columns into appropriate formats.
7. Created additional Month, Day, and Hour columns.
8. Analyzed sales by product line.
9. Analyzed sales by branch and city.
10. Analyzed customer types and gender.
11. Analyzed payment methods.
12. Analyzed daily, monthly, and hourly sales.
13. Analyzed customer ratings.
14. Studied the relationship between Quantity and Total Sales.
15. Created a correlation heatmap.
16. Summarized the key findings.

## Key Findings

- Total sales were **322,966.75**.
- Average transaction value was **322.97**.
- Average customer rating was **6.97**.
- **Food and beverages** had the highest total sales among product lines.
- **Branch C** recorded the highest sales among branches.
- **Naypyitaw** recorded the highest sales among cities.
- **Members** recorded the highest sales among customer types.
- **Ewallet** was the most frequently used payment method.
- The highest sales occurred around **7 PM**.
- The correlation between Quantity and Total Sales was approximately **0.71**, indicating a positive relationship.

## Visualizations

The project includes visualizations for:

- Sales by Product Line
- Sales by Branch
- Sales by City
- Sales by Customer Type
- Sales by Gender
- Payment Method Distribution
- Daily Sales Trend
- Monthly Sales
- Sales by Hour
- Average Rating by Product Line
- Rating Distribution
- Quantity vs Total Sales
- Correlation Heatmap

## Project Structure

```text
CODTECH_EDA_supermarket/
│
├── dataset/
│   └── supermarket_sales.csv
│
├── notebook/
│   └── Supermarket_Sales_EDA.ipynb
│
├── visualizations/
│   ├── average_rating_by_product.png
│   ├── correlation_heatmap.png
│   ├── daily_sales_trend.png
│   ├── monthly_sales.png
│   ├── payment_method_distribution.png
│   ├── quantity_vs_total_sales.png
│   ├── rating_distribution.png
│   ├── sales_by_branch.png
│   ├── sales_by_city.png
│   ├── sales_by_customer_type.png
│   ├── sales_by_gender.png
│   ├── sales_by_hour.png
│   └── sales_by_product_line.png
│
├── screenshots/
│   ├── 01_data_quality.png
│   ├── 02_product_sales.png
│   ├── 03_sales_by_hour.png
│   ├── 04_payment_analysis.png
│   └── 05_correlation_heatmap.png
│
└── README.md
Conclusion

The project demonstrates how Python-based data analysis tools can be used to clean, explore, visualize, and interpret supermarket sales data. The analysis provides insights into sales performance, customer behavior, product lines, payment methods, time-based sales patterns, and numerical relationships.

Author
VISHALI_MALLELA