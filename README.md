# Sparkify - Data Modeling with Cassandra
Sparkify - Data Modeling with Cassandra - Udacity Data Engineering Expert Track.

In this project, I built an ETL pipeline using Python, and created Apache Cassandra tables using CQL for a particular analytic focus which is analyze Sparkify's collected data on songs and user activity on their new music streaming app. Then, wrote an ETL pipeline that transfers data from CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.
## Project Datasets:

- event_data:

  CSV files which partitioned by date


## Project Details:

The project purpose is analyze the Sparkify collected data on songs and user activity on their new music streaming app, to understand what songs users are listening to and answer given questions, by analyze the their activities data.

For this analysis; I processed the ```event_datafile_new.csv``` dataset to create a denormalized dataset, then modeled the data tables and the needed queries, finally loaded the data into Apache Cassandra tables and run the queries

## Tools and Technologies:
- Python 3.
- Pandas, NumPy, Psycopg2 Python Libraries.
- ETL: Extract, Transform, Load Data
- Big Data and NoSQL concepts.
- CQL.
- Jupyter Notebook.

## Project Steps:
- 1- Design tables to answer the given queries.
- 2- Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements.
- 3- Develop the CREATE statement for each of the tables to address each query.
- 4- Load the data with INSERT statement for each of the tables.
- 5- Test by running the proper select statements with the correct WHERE clause.


## How To Run The Project?

- 1- Install Python 3.
- 2- Install Apache Cassandra.
- 3- Download the scripts and the datasets.
- 4- Run the Jupyter Notebook project.
