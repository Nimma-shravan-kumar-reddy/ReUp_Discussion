# ReUp_Discussion
# Technical-Skill-Showcase
This repository showcases my technical abilities in Python and SQL, focusing on ETL processes and SQL querying.

# Project 1: ETL Process
This project, documented in the Jupyter Notebook ETL.ipynb, shows an ETL (Extract, Transform, Load) process applied to stock data. The process is divided into several steps:

`Data Extraction:` Three different sources (tiingo, stooq, and Yahoo Finance) are used to extract Amazon's stock data from June 2018 to the present day.

`Feature Selection:` The data from all sources are trimmed to include only 'Open', 'High', 'Low', and 'Close' columns.

`DataFrame Formatting:` The DataFrames from all sources are formatted to have a common structure, column names, and indices. The order of rows in the 'stooq' DataFrame is also corrected.

`Data Merging:` The data from all sources are merged together, and in the case of duplicate data, the mean value is used.

`Data Loading:` The merged data is loaded into an SQLite database for persistent storage.

You can view this project in the ETL.ipynb file.

# Project 2: SQL Queries
This project, documented in the Jupyter Notebook SQL Queries.ipynb, demonstrates the ability to work with SQLite databases and SQL queries in Python.

Database and Table Creation: An SQLite database is created and a table named 'admissions' is defined within it.

`Data Insertion:` Data from a CSV file is loaded into a DataFrame and then inserted into the 'admissions' table in the SQLite database.

`Data Extraction:` Data is extracted from the SQLite database and loaded into a DataFrame.

`Querying the Database:` Several queries are executed to filter data based on certain conditions.

`Data Updating:` The database is updated by modifying a specific row in the 'admissions' table.

You can view this project in the SQL Queries.ipynb file.

# Requirements
To run these notebooks, you'll need to have Python installed along with the following libraries:

- pandas
- pandas_datareader
- yfinance
- matplotlib
- sqlite3

# Python Challenge
This challenge consists of python code approach for building recommendation system.
