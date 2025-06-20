🏅 Paris Olympic Data Analysis with Apache Spark

This project explores Paris Olympic datasets using Apache Spark (PySpark) on Databricks Community Edition. It highlights how Spark's distributed data processing can uncover insights into athlete participation, gender trends, coaching roles, and medal performance.

🔧 Tools & Technologies

    Apache Spark (PySpark)

    Databricks Community Edition

    Python

    Git & GitHub
    
📁 Datasets Used

Stored in /FileStore/tables/ on Databricks:

    Athletes.csv

    Coaches.csv

    EntriesGender.csv

    Teams.csv

    Medals.csv

📊 Key Analyses Performed

    ✅ Top countries by number of athletes and coaches

    ✅ Athletes and coaches involved in multiple disciplines or events

    ✅ Gender participation breakdown (male vs. female)

    ✅ Disciplines with more female than male participants

    ✅ Medal counts and team entries by discipline and country

🚀 Apache Spark Concepts Used

    DataFrame API: Core operations for data loading, transformation, and filtering

    Transformations: select, filter, groupBy, agg, orderBy, distinct, withColumn

    Aggregations: count, sum, max, min, countDistinct

    Data Types: Used StructType, StructField, and schema inference

    SQL: Queried registered tables using %sql in Databricks notebooks

    Hive Integration: Saved processed data to Hive metastore tables
