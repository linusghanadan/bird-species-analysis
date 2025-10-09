# Bird Species Egg Volume Variation Analysis

## Analysis Summary

Created SQLite database from CSVs and schema build script, queried to fetch distinct species names, created cursor, and stored species data. Iterated over species data, querying the database to fetch egg volume data for each species, loading data into pandas DataFrame, and computing coefficients of variation for each species.

## SQLite Database

The code in the ipnyb file uses the SQLite database that is included in this repository. This database was created by converting the DuckDB database, which is also included in this repository. The DuckDB database was converted to SQLite because the SQLite version accepts null egg numbers.

## DuckDB Database

The DuckDB database was created using a collection of files that can be found in the 'database-build-files' folder in this repository. This database was created as a project for the Databases & Data Management course at the Bren School at UC Santa Barbara.
