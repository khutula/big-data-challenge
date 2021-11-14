# GT Bootcamp Big Data Homework: "Alexa, can you handle big data?"

## Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Technologies & Tools](#technologies)
4. [Files & Links](#files)

<a name="introduction"></a>
### Introduction
In this assignment, I have been tasked with utilitzing cloud capabilities on the ETL process with two Amazon review datasets. The datasets I selected from the [list](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) are Pet Products v1_00 and Digital Ebook Purchases v1_01.

<a name="objectives"></a>
### Objectives
Extract, Transform, and Load big data by:
* Reading in both datasets from Amazon S3 into a Spark DataFrame
* Creating a database linked to an Amazon RDS in PostgreSQL
* Load the table schemas into the database
* Ensuring column datatypes match the datatypes for each table in PostgreSQL
* Creating four separate dataframes to match the respective table schemas
* Performing any necessary data transformations or calculations
* Connecting to the PostgreSQL RDS database
* Loading each dataframe into the respective tables in PostgreSQL

<a name="technologies"></a>
### Technologies & Tools
This project uses: 
* Python
* Spark
* Pyspark
* SQL
* PostgreSQL
* Jupyter Notebook
* Google Colab
* Amazon RDS
* Amazon S3 Buckets

<a name="files"></a>
### Files & Links

* [Pet Product ETL Notebook](level-1/dataset_1_etl.ipynb): notebook used for ETL for the pet product review data
* [EBook ETL Notebook](level-1/dataset_2_etl.ipynb): notebook used for ETL for the ebook review data
* [Table Schema](level-1/Resources/schema.sql): schema used for the four tables in PostgreSQL


