# EV Population Database Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Files in This Project](#files-in-this-project)
   - [SQL Script](#1-annotated-group_6_ev_population-1sqlpdf)
   - [SQL Queries](#2-annotated-group_6_ev_population_queries-1txtpdf)
   - [Entity-Relationship Diagram](#3-grop_6_ev_population_erd_diagram-1mwb)
3. [Key Features](#key-features-of-the-database)
4. [How to Use](#how-to-use)
5. [Contributors](#contributors)
6. [License](#license)

## Project Overview
This project focuses on analyzing the population of electric vehicles (EVs) using a structured MySQL database. The database stores and manages information related to electric vehicles, including their make, model, year, type, location, and electric range. The project includes an entity-relationship diagram (ERD), SQL scripts for database creation and querying, and a set of SQL views for extracting meaningful insights.

## Files in This Project
### 1. **annotated-Group_6_ev_population-1.sql.pdf**
   - This file contains the SQL script for creating the EV population database.
   - It includes table structures such as `vehicle`, `model`, `electric_vehicle_type`, `electric_utility`, and `location`.
   - It also defines relationships between tables using foreign keys and primary keys.
   - Some views are included, such as `brand_median_and_percentage`, which calculates the percentage of total vehicles per brand, and `electric_vehicle_details`, which provides details about each EV.

### 2. **annotated-Group_6_ev_population_queries-1.txt.pdf**
   - This document contains SQL queries designed to retrieve and analyze data from the EV database.
   - Queries include:
     - `Electric_Vehicle_Details`: Provides details of EVs, including make, model, year, and electric range.
     - `Model_Availability_By_Location`: Shows how many locations have a particular model available.
     - `PHEV_Range`: Lists plug-in hybrid EVs with their electric range.
     - `EV_Totals`: Calculates the total number of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs), identifying the most popular model.
     - `Brand_Median_and_Percentage`: Computes the median electric range for each brand and its share of the total EV population.

### 3. **Grop_6_EV_Population_ERD_Diagram-1.mwb**
   - This file contains the entity-relationship diagram (ERD) for the EV database.
   - The ERD visually represents the relationships between key entities like vehicles, models, locations, and electric utilities.
   - It provides a structured overview of how data is interconnected, aiding in database design and query optimization.

## Key Features of the Database
- **Comprehensive EV Data Storage**: Includes information on EV make, model, type, electric range, and MSRP.
- **Geographical Analysis**: Tracks where different EV models are located.
- **Statistical Insights**: Uses SQL views to calculate EV distributions, median ranges, and brand percentages.
- **Efficient Querying**: Provides optimized SQL queries for retrieving and analyzing data.

## How to Use
1. **Database Setup**
   - Load the SQL script from `annotated-Group_6_ev_population-1.sql.pdf` into MySQL.
   - Execute the script to create tables and insert data.
   - Run the queries from `annotated-Group_6_ev_population_queries-1.txt.pdf` to extract insights.

2. **Understanding Data Relationships**
   - Refer to the ERD file (`Grop_6_EV_Population_ERD_Diagram-1.mwb`) to visualize table relationships.

3. **Performing Analysis**
   - Use provided queries to analyze EV distributions, identify popular models, and compare brand performance.


## License
This project is for educational purposes and is free to use and modify.

