# Bird Species Egg Volume Variation Analysis

## Context

This project was completed for my Databases & Data Management class, taken as part of my Master's program at UC Santa Barbara. Provided with data and questions, I carried out this analysis myself.

## Summary of Analysis

For the project, we were provided three datasets from the Arctic Shorebird Demographics Network (ASDN). Our instructions were to create an Entity-Relationship model to understand how the variables related to each other across the three datasets to create a set of tables with fields from the datasets and additional code fields to use as primary keys, translate this model into a schema build SQL script to create a database, and then also answer a data analysis question through querying our database and executing an iterative calculation over results using Python.

## Entity-Relationship Model
The entities and relationships outlined in the following diagram were used to construct the schema build SQL script.
<img width="874" height="888" alt="asdn-er-diagram" src="https://github.com/user-attachments/assets/933469cc-75c3-4a9f-8d1a-7836dc080472" />

## Notes on Databases Created

#### database.db

The DuckDB database (named database.db) is found in the 'database-build-files' folder, and was created using the other files in the same folder, including CSVs sourced from the [Arctic Shorebird Demographics Network (ASDN)](https://www.manomet.org/project/arctic-shorebird-demographics-network-asdn/).

#### database.sqlite

The SQLite database (database.sqlite), created through converting the DuckDB database, was used to conduct the project's analysis. 
The DuckDB database was converted to SQLite because the SQLite version accepts null egg numbers.

