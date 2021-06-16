# Movies-ETL
Extract movie data from Wikipedia and Kaggle; clean and transform data; Load clean data to SQL database

## Deliverable 1: Extract-Transform-Load (ETL) JSON and CSV file data to Pandas dataframes
The provided script ETL_function_test.ipynb includes a function that reads the provided data files (see Resources) and creates three separate DataFrames for parsing.

## Deliverable 2: Extract and Transform Wikipedia data to merge with Kaggle movie data
The provided script ETL_clean_wiki_movies.ipynb will clean extracted data by removing unnecessary and redundant columns, extract the IMDb ID for each movie, and uses regular expressions to clean and format data.

## Deliverable 3: Extract and Transform Kaggle data to merge with Wikipedia movie data
The provided script ETL_clean_kaggle_data.ipynb will clean extracted data downloaded from Kaggle, then convert the clean data into dataframes.  Finally, the Kaggle and Wikipedia data will be merged to create a single, complete movie dataframe.

## Deliverable 4: Create a Movie Database
The provided script ETL_create_database.ipynb will build on the script created in Deliverable 3 and convert the completed movies_df Pandas DataFrame and MovieLens rating CSV data to a SQL database (PostgreSQL).