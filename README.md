This project demonstrates the design and implementation of a scalable ETL pipeline for Anti-Money Laundering (AML) transaction monitoring. Utilizing AWS services, the project begins by migrating a database from PostgreSQL to an Aurora MySQL database. It then extracts data from the Aurora MySQL, processes it with AWS Glue, and stores the processed data in S3 for analysis with Amazon Athena. Perfect for those interested in data engineering, finance, and compliance, this guide highlights practical decisions in cost control and security (including the principles of least privilege), providing a robust and hands-on project experience.

![image](https://github.com/Ibrahim-Maiga/ETL-Pipeline-For-Migrating-Processing-And-Querying-AML-Transactions/blob/main/AML-Project-Architecture-Diagram.png)

**Data source**: https://www.kaggle.com/datasets/berkanoztas/synthetic-transaction-monitoring-dataset-aml
