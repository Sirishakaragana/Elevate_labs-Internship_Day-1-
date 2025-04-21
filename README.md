# Elevate_labs-Internship_Day-1-
Internship-Day1

#####Netflix Dataset Cleaning - Elevate Labs (Task 1, Day 1)

To clean and preprocess a raw Netflix dataset using Python and Pandas by handling missing values, removing inconsistencies, and preparing it for analysis or modeling.

#####Cleaning Steps

Checked for missing values in the director, cast, country, date_added, and rating columns.

Filled the missing values with the following:

director: 'Unknown'

cast: 'Not Provided'

country: 'Unknown'

rating: 'Not Rated'

date_added: Used forward fill method (used the previous row's value)

Converted the date_added column to datetime format.

Cleaned and formatted text in columns like title, country, and listed_in by using title case and removing extra spaces.

Renamed all column headers to lowercase and used snake_case format for consistency.

Checked for and confirmed that there were no duplicate rows in the dataset.

The final dataset is cleaned, well-structured, and ready for further analysis

#####Files Included

Elevate_labs(Task_1_Day_1).ipynb: This notebook contains the full code used for cleaning the dataset.

cleaned_netflix_data.csv: The cleaned version of the Netflix dataset.

README.md: A summary of what was done during this task.

####Tools Used
Python 3
Pandas
Google Colab
