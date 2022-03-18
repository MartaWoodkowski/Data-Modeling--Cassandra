# Data-Modeling--Cassandra

A startup called Sparkify wanted to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team was particularly interested in understanding what songs users are listening to. There wasn't an easy way to query the data to generate the results, since the data resided in a directory of CSV files on user activity on the app.

I created an Apache Cassandra database for the analysis. 

In this project I did the following:
* Designed tables to answer the queries outlined in the project template.
* Wrote Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements.
* Developed my CREATE statement for each of the tables to address each question.
* Loaded the data with INSERT statement for each of the tables. Included IF NOT EXISTS clauses in my CREATE statements to create tables only if the tables do not already exist. 
* Built ETL Pipeline (using Python).
* Implemented the logic in section Part I of the notebook template to iterate through each event file in event_data to process and create a new CSV file in Python.
* Made necessary edits to Part II of the notebook template to include Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables in the data model.
* Tested by running SELECT statements after running the queries on my database.