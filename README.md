# Olist E-Commerce Sales Analytics

An end-to-end data analytics project exploring Brazilian e-commerce sales using **Python, SQL, Statistics, Sales Forecasting, and Power BI**.

## Project Overview

This project analyzes the Olist Brazilian E-Commerce dataset to identify sales trends, evaluate business performance, understand customer behavior, and investigate factors affecting delivery times and customer satisfaction.

The project follows a complete analytics workflow, from data loading and exploratory analysis to statistical testing, sales forecasting, and interactive dashboard development.

## Objectives

- Analyze overall sales and revenue performance.
- Identify top-performing product categories and sellers.
- Understand customer purchasing behavior and geographic distribution.
- Evaluate payment methods and installment patterns.
- Analyze delivery performance and its relationship with review scores.
- Apply statistical methods to investigate business questions.
- Forecast future sales trends.
- Build an interactive Power BI dashboard for business insights.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and forecasting |
| Pandas and NumPy | Data manipulation and numerical analysis |
| Matplotlib and Seaborn | Data visualization |
| SciPy | Statistical hypothesis testing |
| Jupyter Notebook | Analysis workflow and documentation |
| SQL | Data querying and business analysis |
| Power BI | Interactive dashboard and KPI reporting |

## Project Structure

```text
olist-sales-analytics/
│
├── python/
│   ├── 01_data_loading.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_statistical_analysis.ipynb
│   └── 04_sales_forecasting.ipynb
│
├── sql/
│   ├── schema.sql
│
├── power-bi/
│   └── Olist_Sales_Dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
├── README.md
└── .gitignore
```

*The structure above is the recommended organization. Keep only files and folders that actually exist in your repository, and adjust filenames if yours are different.*

## Project Workflow

### 1. Data Loading and Preparation

- Loaded the Olist dataset into Python using Pandas.
- Inspected dataset dimensions, column types, missing values, and duplicate records.
- Reviewed relationships between orders, customers, products, sellers, payments, and reviews.
- Prepared the data for exploratory and statistical analysis.

### 2. Exploratory Data Analysis (EDA)

Conducted business-focused analysis across multiple areas:

- **Sales:** Revenue, order volume, average order value, and monthly trends.
- **Products:** Product categories, pricing, and sales performance.
- **Customers:** Customer spending, order frequency, and geographic distribution.
- **Sellers:** Seller performance and revenue contribution.
- **Payments:** Payment methods and installment patterns.
- **Delivery:** Delivery duration and order status.
- **Reviews:** Review-score distribution and customer satisfaction.
- **Geography:** Customer, seller, and revenue distribution by state.

### 3. Statistical Analysis

Applied descriptive statistics and inferential methods to investigate business relationships.

- Calculated means, medians, variance, standard deviation, skewness, and confidence intervals.
- Examined correlations between order value, delivery duration, and review scores.
- Used Spearman rank correlation to evaluate the relationship between delivery time and review score.
- Applied the Mann–Whitney U test to compare delivery times and order values across review-score groups.
- Interpreted statistical significance in the context of business performance.

### 4. Sales Forecasting

Used historical sales data to investigate future sales trends.

This section covers the forecasting approach, model evaluation, and forecast visualization.

**Forecasting model:** Add the model actually used in `04_sales_forecasting.ipynb`.

**Evaluation metrics:** Add the metrics actually calculated, such as MAE, RMSE, or MAPE.

**Key result:** Add your verified forecast findings after completing the analysis.

### 5. Power BI Dashboard

Developed an interactive dashboard to monitor business performance and explore sales trends.

Dashboard features include:

- Total Revenue
- Total Orders
- Total Items Sold
- Average Order Value
- Monthly Revenue Trends
- Revenue by Product Category
- Monthly Order Volume
- Payment Method Analysis
- Order Status Distribution
- Customer Review Scores
- Revenue by Customer State
- Top 10 Product Categories
- Average Delivery Time
- Interactive date, product category, customer state, and payment type slicers

## Key Business Metrics

Initial analysis produced the following results. Values should be interpreted according to the project's metric definitions.

| Metric | Result |
|---|---:|
| Total Orders | 99,441 |
| Customers | 96,096 |
| Products | 32,951 |
| Sellers | 3,095 |
| Items Sold | 112,650 |
| Total Product Revenue | 13,591,643.70 |
| Average Order Value | 137.75 |
| Average Review Score | 4.09 / 5 |

*Revenue represents product prices and excludes freight charges. Average order value should be interpreted using the specific order-value calculation used in the analysis.*

## Dataset

The project uses the **Olist Brazilian E-Commerce Public Dataset**, originally published on Kaggle.

The data contains information about orders, customers, order items, products, sellers, payments, and reviews.

Dataset source: [Olist Brazilian E-Commerce Dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The raw dataset is not included in this repository. Obtain it from the original source and follow its applicable terms.

## How to Run the Project

1. Clone or download this repository.
2. Obtain the dataset from the source listed above.
3. Install Python and Jupyter Notebook.
4. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scipy jupyter
   ```

5. Update the notebook data paths to match your local dataset location.
6. Open the notebooks in the `python/` directory and run the cells in order.
7. Open the `.pbix` file using Power BI Desktop to explore the dashboard.
8. Use a compatible SQL database to execute the SQL scripts, adapting syntax if necessary.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- Business intelligence and KPI development
- Statistical inference and hypothesis testing
- Correlation analysis
- Sales forecasting
- SQL querying and data modeling
- Data visualization and dashboard development
- Business insight communication

## Future Improvements

- Compare multiple forecasting models.
- Add forecast confidence intervals and model diagnostics.
- Improve dashboard drill-through and tooltip functionality.
- Automate data preparation and reporting.
- Add additional business recommendations supported by the analysis.

## Author

**Data Analytics Portfolio Project**

This project demonstrates an end-to-end approach to transforming raw e-commerce data into statistical insights, sales forecasts, and interactive business reporting.
