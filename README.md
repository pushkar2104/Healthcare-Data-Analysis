# Healthcare-Data-Analysis

## Analyzing Healthcare data using AWS data engineering services and providing insights.

--- This project demonstrates a data engineering pipeline for analyzing data from Kaggle using a combination of AWS services:

1.Data Ingestion:
Kaggle dataset is downloaded and uploaded to an Amazon S3 bucket.

2.Data Discovery and Cataloging:
AWS Glue Crawler scans the data in S3 and creates a table in the AWS Glue Data Catalog, providing schema information and metadata.

3.Data Transformation and Enrichment:
AWS Glue ETL jobs are used to:
Clean and transform data.

4.Data Analysis and Visualization:
Amazon Athena is used to query the transformed data stored in S3.
Amazon QuickSight is used to create interactive dashboards and visualizations based on the Athena query results.

# Technologies Used:
AWS S3
AWS Glue
AWS Athena
Amazon QuickSight
Kaggle


