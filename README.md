## Introduction

The purpose of this project is to build an ETL pipeline that will be able to extract song and log data from an S3 bucket, process the data using Spark and load the data back into s3 as a set of dimensional tables in spark parquet files. This helps analysts to continue finding insights on what their users are listening to.

## Database Schema Design

![Our Database looks like the following](https://github.com/hamadalaqeel/data-lake-aws/blob/master/Database%20Schema.png)

## Instructions
- Add appropriate AWS IAM Credentials in `dl.cfg`
- Specify desired output data path in the main function of `etl.py`
- Run `etl.py`
