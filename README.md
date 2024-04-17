# Database Design, ETL, and Analytics of Chicago Crime Data: Unveiling Insights and Patterns

This project explores the Database Design, ETL (Extract, Transform, Load), and Analytics phases using a multi-year Chicago crime data source. The project is structured into two main parts:

## Data source
[Chicago Crime Data Dashboard (2001 to present)](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present-Dashboard/5cd6-ry5g)

## About the Data
This dataset reflects reported incidents of crime in the City of Chicago from 2001 to the present, minus the most recent seven days. It is sourced from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. To protect the privacy of crime victims, addresses are shown only at the block level, and specific locations are not identified. For queries about this dataset, contact the Data Fulfillment and Analysis Division at DFA@ChicagoPolice.org.

## Project in Parts

### Part I: Database Design and ETL
- **Reverse Engineering**: Reverse engineer an existing source RDBMS using metadata SQL queries to identify table and attribute details necessary for creating tables and an entity-relationship diagram depicting the database's logical structure. The source data is in an SQLite database.
- **DDL Implementation**: Implement a set of tables using DDL in your SSO `dsa_student` database schema on the Postgres server, replicating the source database structure.
- **ER Diagram**: Create an Entity Relationship Diagram.
- **Database Connections**: Establish connections to the source and destination databases.
- **ETL Process**:
  - Extract the source data from tables.
  - Transform values as required.
  - Load into the destination tables.
  - Validate the ETL process by confirming row counts in both source and destination tables.

### Part II: Analytics
- **Query Design and Execution**: Perform data querying to prepare for analysis.
- **Analytics and Insights**: Analyze the data to unveil insights and patterns.

## About the Repository
- **Readme**
- **Activity**
- **Stars**: 0 stars
- **Watchers**: 1 watching
- **Forks**: 0 forks
- **Report repository**
- **No releases published**
- **No packages published**
- **Primary Language**: Jupyter Notebook
