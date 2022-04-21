# Movies-ETL

## Objective
* Create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. 
* Refactor the code from this module to create one function, which:
	* Extracts data from the three files from Wikipedia, Kaggle, and the MovieLens ratings.
	* Transforms the data with regex and functions.
	* Loads the data into a PostgreSQL database.

## Results:

The database output consists of two tables: A table for movies data with 6,052 rows representing unique movie titles, and another table for ratings data with 26,024,289 unique rows displaying a viewer rating of 1-5.