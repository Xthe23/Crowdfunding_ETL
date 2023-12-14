# Crowdfunding ETL Project

## Overview
This project involves an ETL (Extract, Transform, Load) process for a crowdfunding dataset. The goal is to extract data from various sources, transform it into a structured format, and load it into a database for analysis.

## Contents
- `ETL_Mini_Project_MKravitz_CLillge.ipynb`: Jupyter Notebook containing the ETL process.
- `Resources/`: Directory containing all the data files and SQL scripts.
  - `campaign.csv`: Campaign data.
  - `category.csv`: Category data.
  - `contacts.csv`: Contacts data.
  - `subcategory.csv`: Subcategory data.
  - `crowdfunding.xlsx`: Original crowdfunding data in Excel format.
  - `contacts.xlsx`: Contacts data in Excel format.
  - `crowdfunding_db_schema.sql`: SQL script for creating the database schema.
  - `table_queries.txt`: SQL queries for data extraction.

## Database Schema
The database schema is defined in `crowdfunding_db_schema.sql`. It includes tables for campaigns, contacts, categories, and subcategories, with appropriate relationships and constraints.

## Data Transformation
The transformation process is detailed in `ETL_Mini_Project_MKravitz_CLillge.ipynb`. It involves:
- Reading and cleaning data from Excel files.
- Splitting categories and subcategories.
- Formatting and normalizing data.
- Exporting transformed data to CSV files.

## Loading Data
The final step involves loading the transformed data into a database, as defined by the schema in `crowdfunding_db_schema.sql`.

## Usage
To use this project:
1. Clone the repository.
2. Run the Jupyter Notebook to perform ETL.
3. Execute the SQL script to create the database schema.
4. Load the CSV files into the database.


## Collaborators
- Cole Lillge & Michael Kravitz

## Acknowledgments
Thanks to all contributors and supporters of this project.
