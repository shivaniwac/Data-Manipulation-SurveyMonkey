# Data-Manipulation-SurveyMonkey
This script processes SurveyMonkey data collected from an employee question-answer survey. The company is interested in two key metrics:

Respondents with Non-Null Answers: How many respondents provided answers without any null values.
Repeated Answers by the Same Respondent: How many answers were given by the same respondent two or more times.
The data manipulation involves several steps using Python with the pandas and os libraries:

Importing Datasets: Load different sheets from an Excel file.
Renaming Columns: Update column names for better readability and consistency.
Data Grouping and Analysis: Perform grouping operations to count unique respondents and identify repeated answers.
Creating Final Output: Generate a final sheet with the manipulated data and save it as an Excel file.
