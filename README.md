# ETL-Project
This project is an ETL pipeline built to process sales data, clean and transform raw datasets, and prepare them for analytics and reporting.
# Tools & Technologies
- Pentaho Data Integration (Kettle)
- PostgreSQL
- SQL
- Data Cleaning & Transformation
# Dataset
Number of records: 51,273 rows
- Sales_Product dataset: 88,475 records
- Global Superstore dataset: 51,273 records
- Total data processed: 139,748 records
# ETL Pipeline
1. Extract data from CSV
2. Transform data (clean missing values, format date, remove duplicates)
3. Load into PostgreSQL database
## ETL Workflow
### Data Transformation Steps
- Split product hierarchy (line/type/product)
- Encode categorical variables (Ship Mode)
- Feature engineering (Average_Income)
- Data cleaning (missing values, formatting)
# Key Results
- Improved data quality and consistency
- Enabled efficient querying for analytics
- Prepared dataset for reporting and machine learning
