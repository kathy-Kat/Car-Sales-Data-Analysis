--- first create your database
CREATE DATABASE data_analytics_practice;

--- do this at the start of all new queries to make sure you reference the right database. 
--- You can running your queries unless you do this first.
USE data_analytics_practice;

--- check that your database exists
SHOW DATABASES;

--- then create a new table
CREATE TABLE car_sales_cleaned;

--- checking that your table exists
SHOW TABLES;

--- checking all values from orginal table
SELECT *
FROM car_sales_to_be_analised;

--- Then create the new table for cleaned values 
--- This will be for the corrections once you start analysing your data
CREATE TABLE car_sales_cleaned AS
SELECT *
FROM car_sales_to_be_analised;

--- checking all values from the "newly created" table to be cleaned
SELECT *
FROM car_sales_cleaned;

--- checking all the column/ group names and data types
describe car_sales_to_be_analised;
