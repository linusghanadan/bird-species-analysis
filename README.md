# Bird Species Egg Volume Variation Analysis

## Context

This project was completed for my Databases & Data Management class, taken as part of my Master's program at UC Santa Barbara. Provided with data and questions, I carried out this analysis using appropriate data modeling and database techniques.

## Summary of Analysis

Created SQLite database from CSVs and schema build SQL script, queried to fetch distinct species names, created cursor, and stored the species data. Iterated over species data, querying the database to fetch egg volume data for each species, loading data into pandas DataFrame, and computing coefficients of variation for each species.

## Entity-Relationship Model
The entities and relationships outlined in the following diagram were used to construct the schema build SQL script.
<img width="874" height="888" alt="asdn-er-diagram" src="https://github.com/user-attachments/assets/933469cc-75c3-4a9f-8d1a-7836dc080472" />

## Notes on SQLite Database

The code in the ipnyb file uses the SQLite database that is included in this repository. This database was created by converting the DuckDB database, which is also included in this repository. The DuckDB database was converted to SQLite because the SQLite version accepts null egg numbers.

## Notes on DuckDB Database

The DuckDB database was created using a collection of files that can be found in the 'database-build-files' folder in this repository. This database was created as a project for the Databases & Data Management course at the Bren School at UC Santa Barbara.
