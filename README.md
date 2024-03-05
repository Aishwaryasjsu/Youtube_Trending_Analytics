# Youtube_Trending_Analytics
## This projects provides moving data from on-premise to cloud using cloud services.Creating pipelines to clean data and provide insight into trending video to analyse the trend in different locations.
## learnt:
AWS services-IAM roles,S3,Athena,Lamda,Trigger, Lamda Layers,Glue(crawlers,catalogs,tables, ETL jobs).
Visualization-Quick sight, Tableau
Schdueling -Apache Airflow

## Steps 
1. Extracted data from website and loaded into s3 buckets using aws cli.
2. Cleaned raw data and loaded data into cleaned buckets transforming json(issue like serde and multiple tags) data into parquet.
3. For cleaning and transformtion used lamda function , S3 triggers and lamda layers.
4. Worked on dataype to make them compatible in both source and target .
5. Used Glue to load data using crawler, creation of catalogs and tables and quired it using Athena.
6. Created data pipelines in glue studio joined data of different format csv and parquet to build reportng table.
7. Created analtyical table for reporting with aggregated,summarised data.
8. Used this table as data sources to create dashboards in Quick Sight-helps to analyse data on basis of region, comments, location, categories.
9. Used S3 triggers and Airflow to schduele jobs and update data as per the changes.

## Screenshots:
https://docs.google.com/document/d/1Jn_36uijA2qk-Egh7ezYP-nLTKJYVSW9Gmma7zerAWM/edit
## Dashboards:
![image](https://github.com/Aishwaryasjsu/Youtube_Trending_Analytics/assets/111553278/c835f8ee-e9a5-4db7-8aa5-d91617bcbfd8)
![image](https://github.com/Aishwaryasjsu/Youtube_Trending_Analytics/assets/111553278/5d1d832b-cd53-4cc0-9921-a21734d8fb6f)
![image](https://github.com/Aishwaryasjsu/Youtube_Trending_Analytics/assets/111553278/4dc5c5ad-16f7-401b-8e64-9bc4df360f88)

https://github.com/Aishwaryasjsu/Youtube_Trending_Analytics/assets/111553278/57d3f6b1-1af7-447f-bb69-b7292b584d01



