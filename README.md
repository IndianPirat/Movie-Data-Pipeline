# Movie-Data-Pipeline

# Project Overview

This project demonstrates a basic ETL pipeline for processing movie data. The pipeline performs the following steps:

- Extract: Data is fetched from the TMDB API.
- Transform: The movie data is transformed using PySpark for data cleaning and processing.
- Load: Cleaned data is loaded into a PostgreSQL database.
- Automation: Airflow automates the ETL process, ensuring new data is fetched daily at the same time.

Once the data pipeline is in place, we will create a Movie Data Website where users can search for a movie and get detailed movie information back like genre, rating and more
For the Frontend we use Svelte and Bootstrap and for the Backend we use FastAPI

# Project Status

Currently not finished

# Tech Stack 

- Python
- PostgreSQL
- PySpark
- Airflow
- FastAPI
- Svelte
- Bootstrap
