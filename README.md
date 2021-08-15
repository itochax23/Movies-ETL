# Movies-ETL

## Overview

We have extracted scraped Wikipedia data stored as a JSON, and Kaggle data stored in CSVs. We then used Python and Pandas to explore, document, and perform our data transformation. We have determined that a SQL database is the best solution for sharing the data in the hackathon, so we loaded our data into a PostgreSQL table. 

Taking it further we need to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We've refactored the code to create one function that takes in the three data sources and performs the ETL process by adding the data to a PostgreSQL database.

Deliverable 1: An ETL Function to Read Three Data Files
Deliverable 2: Extract and Transform the Wikipedia Data
Deliverable 3: Extract and Transform the Kaggle data
Deliverable 4: Movie Database
