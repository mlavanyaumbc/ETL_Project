# ETL Project for Top 10 Largest Banks by Market Capitalization
![WhatsApp Image 2024-10-16 at 7 23 17 AM](https://github.com/user-attachments/assets/0147bcca-ff55-4713-9e64-59051205f470)

## Project Overview
This project is designed to demonstrate the Extract, Transform, Load (ETL) process using Python, with real-world data on the top 10 largest banks by market capitalization.
The primary objective is to gather data, perform transformations for currency conversion, and store the processed data in both a CSV file and a database.
The data will then be accessible for various business units across different countries to query and retrieve bank information in their local currency.

## Project Scenario
You have been hired by a multi-national firm as a Data Engineer to compile a list of the top 10 largest banks in the world, ranked by market capitalization in USD. 
This data needs to be converted to GBP, EUR, and INR based on provided exchange rates.
The transformed data will be stored in a CSV file and an SQLite database for further queries by international offices.

## Project Structure
### Step 1: Data Extraction

Function to extract data from a given URL under the "By Market Capitalization" section.
Save extracted data to a pandas DataFrame.

### Step 2: Data Transformation

Convert the market capitalization values into GBP, EUR, and INR based on provided exchange rates.
Round these values to two decimal places.
Save transformed data to a new DataFrame.

### Step 3: Load to CSV

Save the transformed DataFrame as a CSV file locally.

### Step 4: Load to SQL Database

Create and save the transformed data into an SQLite database as a table for easy querying.

### Step 5: Query the Database

Functions to query the table based on specific country requirements:
London Office (GBP)
Berlin Office (EUR)
New Delhi Office (INR)

### Step 6: Logging

Implement logging throughout each step to track progress and potential issues.
