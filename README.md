# Movies-ETL

#### We did this project as a starting introduction to the ETL process. In this module we refactored code to take 3 files, Wikipedia data, Kaggle metadata, and the MovieLens rating data. It then would take this info and transform in into a PostgreSql database.

## Overview of the Files

### ETL_function_test.ipynb

- Data is extracted from the website in JSON and CSV formats.
- The data is then taken and turned into Pandas Dataframes
- For the JSON file we had to load the file first and then transform into data frame

### ETL_clean_wiki_movies.ipynb

- Function clean_movie combines messy data of names in different languages to a combined cleaner one

- Another function is to clean the columns 


### ETL_clean_kaggle_data.ipynb

- Function extract_transform_load gets new tasks for cleaning Kaggle data and includes:
<br/>- Changing datatypes, using methods pd.to_numeric, astype() and python comparison operators for Boolean types.
<br/>- Filling missing values and filtering unwanted columns.
<br/>- Merging data frames using pd_merge method.

### ETL_create_database.ipynb

- This function connects sqlalchemy library and to_sql method.
- We are able to do the whole process from one ETL call# Movies-ETL