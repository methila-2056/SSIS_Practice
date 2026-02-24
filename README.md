# SSIS Practice Project

## Project Overview
CSV file from flat file source to PostgreSQL using SSIS.

## What this project does
- Reads HR Data CSV file
- Converts employee Full_Name to UPPERCASE using Derived Column
- Loads data into PostgreSQL database

## Tools Used
- SQL Server Integration Services (SSIS)
- PostgreSQL
- Visual Studio 2022

## Data Flow
Flat File Source → Derived Column (UPPER) → ODBC Destination (PostgreSQL)
