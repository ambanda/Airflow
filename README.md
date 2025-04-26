# ETL Pipeline for Credit Scoring

This project implements an ETL pipeline for risk assessment and credit scoring using Python, Apache Airflow, and Delta Lake on S3.

## Features
- **Ingestion**: Data from APIs, internal systems, and public data.
- **Transformation**: Data cleaning, feature engineering, and scaling.
- **Storage**: Delta Lake on S3 for downstream analytics.

## Prerequisites
- Python 3.10
- Apache Airflow
- Spark with Delta Lake
- AWS S3 Bucket

## Setup
1. Clone the repository and navigate to the project directory.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure Airflow and run the DAG:
   ```bash
   airflow dags list
   airflow dags trigger etl_pipeline
   ```

## Folder Structure
- `dags/`: Contains Airflow DAGs.
- `tasks/`: Task scripts for ETL stages.
- `config/`: Configuration settings.

## License
This project is licensed under the MIT License.
