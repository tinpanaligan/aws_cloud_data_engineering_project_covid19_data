# COVID-19 Data Processing Pipeline with AWS Cloud

---

## Overview

This project aims to build a data processing pipeline for COVID-19 data utilizing AWS services such as AWS S3, AWS Glue, AWS Athena, and Python for ETL (Extract, Transform, Load) operations. The pipeline involves uploading COVID-19 data to AWS S3, connecting it to AWS Athena using AWS Glue crawler for schema discovery, exploring the dataset, determining data schema and relational database model with AWS Athena, performing ETL using Python, and finally saving the processed data back to AWS S3 for further analysis.

![AWS_Cloud_Project_Architecture](https://github.com/tinpanaligan/aws_cloud_data_engineering_project_covid19_data/assets/116711183/38b40c3f-dc76-4f94-8419-50109a89f26e)

---

## Components

### 1. COVID-19 Data

- **Source**: COVID-19 data from [AWS COVID-19 data lake](https://aws.amazon.com/covid-19-data-lake/).
- **Purpose**: To analyze and process COVID-19 statistics and trends.

### 2. AWS S3

- **Purpose**: AWS S3 is used as a data lake to store the raw and processed COVID-19 data.
- **Storage**: Raw data is uploaded to AWS S3, and processed data is saved back to AWS S3 for accessibility and long-term storage.

### 3. AWS Glue

- **Purpose**: AWS Glue is used for data cataloging, ETL, and schema discovery.
- **Crawler**: Utilize AWS Glue crawler to connect to the COVID-19 data in AWS S3 and infer its schema.

### 4. AWS Athena

- **Purpose**: AWS Athena is a serverless interactive query service used for analyzing data in AWS S3 using standard SQL.
- **Querying**: Use AWS Athena to explore the dataset, determine its schema, and create relational database models.
- **Integration**: Connect AWS Athena with AWS Glue data catalog for seamless data querying.

### 5. Python ETL Script

- **Purpose**: Python script for Extract, Transform, and Load operations on the COVID-19 data.
- **Execution**: Process raw data, perform necessary transformations, and load the cleaned data back to AWS S3.

---

## How to Run

1. **Upload COVID-19 Data to AWS S3**:
   - Upload the COVID-19 data files to AWS S3 buckets.

2. **Configure AWS Glue Crawler**:
   - Set up an AWS Glue crawler to connect to the COVID-19 data in AWS S3 and infer its schema automatically.

3. **Explore Dataset with AWS Athena**:
   - Use AWS Athena to explore the dataset, determine its schema, and create relational database models.

4. **Perform ETL Using Python**:
   - Develop Python scripts for ETL operations on the COVID-19 data.
   - Execute the scripts to extract, transform, and load the data, ensuring it conforms to the determined schema.

5. **Save Result to AWS S3**:
   - Save the processed data back to AWS S3 buckets for further analysis and visualization.

---

## Project Documentation
[Project Documentation - AWS Cloud COVID19 Data Pipeline](https://alpine-dollar-b3b.notion.site/Project-Documentation-AWS-Cloud-COVID19-Data-Pipeline-ff991aee211f4ab3b5b6be0d411c056a?pvs=4)

---

## Contributors

- Tin Panaligan

---

## Acknowledgments

Special thanks to Darshil Parmar for this project.

---

## Contact Information

For inquiries, please contact tinpanaligan.work@gmail.com.

---

## Appendix: Useful Resources

- [AWS Glue Documentation](https://docs.aws.amazon.com/glue/index.html)
- [AWS Athena Documentation](https://docs.aws.amazon.com/athena/index.html)
- [AWS S3 Documentation](https://docs.aws.amazon.com/s3/index.html)

---
