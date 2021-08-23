# sql-challenge

insert header image here

Contents
* Summary
* Main Task
* 1. Data Modeling
* 2. Data Engineering
* 3. Data Analysis
* Bonus Task
* Dependencies Required
* Folders
* Files


## Summary
In this project I was provided with a set of 6 [CSV files](EmployeeSQL/data) containing Data pertaining to a store, such as employee data and departments data.

3 steps needed to be performed:
1. Data Modeling
2. Data Engineering
3. Data Analysis

## Main Task:

## Data Modeling
The provided [CSV files](EmployeeSQL/data) were inspected to see what kind of data was stored to establish which Data Types and which Relationships needed to be used when creating the Table Schema.

Then an ERD (Entity Relationship Diagram) was created using the [QuickDBD](https://www.quickdatabasediagrams.com/) Web App:


![ERD Diagram](EmployeeSQL/Images/QuickDBD-sql-challenge.png)

## Data Engineering
When creating the diagram the Table Names, Fields, Primary and Foreign Keys, and Data Types and Relationships were entered.

The tool creates an SQL Table Schema which you can export as a SQL file.

The resulting [Table Schema](EmployeeSQL/QuickDBD-sql-challenge.sql) for my diagram.


I created a PostgreSQL database using [pgAdmin](https://www.pgadmin.org/).

Then I entered the code contained in the Table Schema file into the SQL Query Tool and ran the Query to generate the Tables in the database.

Finally, the data from each CSV file was imported to it's relevant SQL Table using pgAdmin. 

## Data Analysis

## Bonus Task

## Dependencies Required
* [Jupyter Notebook](https://jupyter.org/) `pip install notebook`
* [Pandas](https://pypi.org/project/pandas/) `pip install pandas`
* [Matplotlib](https://pypi.org/project/matplotlib/) `pip install matplotlib`
* [SQLAlchemy](https://pypi.org/project/SQLAlchemy/) `pip install SQLAlchemy`
* [Psycopg2](https://pypi.org/project/psycopg2/) `pip install psycopg2`

## Software Used
* Quick DBD Web App
* pgAdmin



## Folders
* All files aside from this README and images used in the README, are stored in the [EmployeeSQL](EmployeeSQL) folder.

* Images for this README file are stored in the [Readme_images](Readme_images/) folder.

* Any diagrams or plots outputted via the code are stored in the [EmployeeSQL/Images](EmployeeSQL/images) folder.

* The original CSV data files that were imported and processed are stored in the [EmployeeSQL/data](EmployeeSQL/data) folder.

## Files



* QuickDBD-sql-challenge.png





