# Database Design, ETL, and Analytics of Chicago Crime Data: Unveiling Insights and Patterns

## Overview
This project delves into the Database Design, ETL (Extract, Transform, Load), and Analytics phases using a comprehensive Chicago crime data set spanning multiple years. The initiative is divided into two pivotal segments: the first focuses on designing and creating a structured database, and the second leverages this database to conduct in-depth analytics and derive actionable insights.

## Data Source
Explore the [Chicago Crime Data Dashboard (2001 to present)](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present-Dashboard/5cd6-ry5g) for comprehensive crime data in Chicago.

## About the Data
This dataset encapsulates reported incidents of crime within the City of Chicago from 2001 to the present, excluding the most recent seven days. Sourced from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system, it aims to protect crime victims' privacy by only showing addresses at the block level without pinpointing specific locations. For further information or inquiries about this dataset, contact the Data Fulfillment and Analysis Division at DFA@ChicagoPolice.org.

## Project Components

### Part I: Database Design and ETL
- **Reverse Engineering**: We begin by reverse engineering an existing source RDBMS using metadata SQL queries. This helps identify table structures and attributes essential for reconstructing the database schema in a new environment.
- **DDL Implementation**: Utilizing DDL, we implement a series of tables within the `dsa_student` database schema on a Postgres server, mirroring the structure of the source database.
- **ER Diagram**: An Entity Relationship Diagram is constructed to visually represent the database's structural blueprint.
- **Database Connections**: We establish robust connections between the source and destination databases to facilitate data flow.
- **ETL Process**:
  - **Extract**: Data is extracted from the source tables.
  - **Transform**: Necessary transformations are applied to ensure data quality and consistency.
  - **Load**: Data is loaded into the destination tables.
  - **Validation**: The ETL process's integrity is confirmed by verifying row counts and data accuracy in both the source and destination tables.

### Part II: Analytics
- **Query Design and Execution**: Sophisticated SQL queries are designed and executed to prepare the data for thorough analysis.
- **Analytics and Insights**: We conduct a detailed examination of the data to unveil critical insights and patterns. This includes identifying trends in crime types, their occurrences, and how they have evolved over time. These insights assist law enforcement agencies and policymakers in strategic planning and resource allocation.

## Key Insights
Through meticulous analysis, we identified several key crime trends in Chicago, such as the prevalence of specific crime types and fluctuations in their occurrence over the past year. Our findings include:
- A notable increase in specific crimes such as theft and assault, highlighting areas requiring enhanced policing and community safety measures.
- Seasonal trends indicating higher crime rates during specific months, which can guide the timing of public safety campaigns.

## Conclusion
This project not only reinforces the importance of structured data analysis in understanding urban crime but also demonstrates how effectively designed databases combined with advanced ETL processes can enhance data accessibility and analytical capabilities.
 forks
- **Report repository**
- **No releases published**
- **No packages published**
- **Primary Language**: Jupyter Notebook
