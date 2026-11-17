# Big Data Sales Analytics

## Project Overview

This project focuses on analyzing sales data using Python, Apache Spark (PySpark), and Hadoop HDFS. It implements a Big Data processing pipeline to ingest, clean, transform, analyze, and store sales data.

The project uses a synthetic dataset containing 10,000 sales records.

## Technologies

- Python
- Apache Spark (PySpark)
- Hadoop HDFS
- Spark SQL
- Pandas
- Matplotlib
- Parquet
- Google Colab

## Project Pipeline

1. **Data Generation:** Generate a sales dataset containing 10,000 records.
2. **Data Ingestion:** Read CSV data using PySpark.
3. **Data Cleaning:** Handle missing values and duplicate records.
4. **Data Transformation:** Calculate total sales revenue.
5. **Data Analysis:** Analyze revenue by product, region, and month.
6. **Spark SQL:** Execute SQL queries for sales analysis.
7. **HDFS Integration:** Store and retrieve sales data using Hadoop HDFS.
8. **Data Storage:** Save processed results in Parquet format on HDFS.
9. **Data Visualization:** Create charts using Matplotlib.

## Project Structure

```text
BigData-Sales-Analytics/
├── BigData_Sales_Analytics.ipynb
├── README.md
├── requirements.txt
└── sales.csv
```

## How to Run

1. Clone this repository.
2. Open `BigData_Sales_Analytics.ipynb` in Google Colab.
3. Install the required Python packages.
4. Run the notebook cells in order.
5. Follow the notebook instructions to configure Hadoop HDFS.

**Note:** Hadoop and Java require separate configuration. HDFS running in Google Colab is an educational, single-machine setup; its files are temporary and may disappear when the runtime resets.

## Project Status

Completed educational project demonstrating a Big Data sales analytics pipeline using PySpark and Hadoop HDFS.

## Author

**Hiba Mrabet**

[GitHub Profile](https://github.com/MrabetHiba)
