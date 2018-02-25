# ETL-Workflow

1) Load data from csv, text, json, avro, parquet files into HDFS

2) Extract data from above loaded files and store in Hive tables i.e. create external Hive tables for above data

3) Create DataFrames from Hive tables

4) Perform following validation and operation on DataFrames:

a) Extract all column name
b) Extract all column name along with their data type
c) Perform filtering on data
d) Perform Join, groupBy, reduceByKey and other operations which requires shuffling
e) Add surrogate id to DataFrames

5) Save DataFrames to HDFS 
