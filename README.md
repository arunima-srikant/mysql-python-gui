# This project was created as a part of coursework to understand how to use GUI in python to display query results.
## Project created by Arunima Srikant (author) and Ayesha Rao.
---
There are two separate sets of instructions below. Once a database has been created, run the code.
### Instructions for data upload in MySQL Workbench
1. Create a database, and give it an appropriate name.
2. Ensure that the csv files are saved as ‘india’, ‘canada’, ‘great_britain’ and ‘united_states’.
3. Before loading the csv files, ensure that the date format for the attribute “trending_date” is as YYYY-MM-DD, and the format for “publish_time” is YYYY-MM-DD HH:MM. The formatting tool in excel will help rectify this issue.
4. Use Table Data Import Wizard for loading data from the following csv files: india, canada, great britain and usa.
5. For the csv file titled category, use the following commands:
CREATE TABLE category(
category_id INT,
category_name VARCHAR(255));
Once this empty table has been created, use the table data import wizard to load the data. Ensure to truncate tables before importing.
### Instructions for running code
Ensure to set appropriate credentials for host, username, password and database name before running the code.
