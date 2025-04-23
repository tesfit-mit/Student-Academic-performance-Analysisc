Student Academic Performance Analysis with Pandas
📊 Student Academic Performance Analysis with Pandas This Python-based project analyzes the academic performance of students using the powerful Pandas library along with Matplotlib and Seaborn for data visualization. The dataset includes student information from various African countries and contains scores in Math, Reading, and Writing.

🔹 Key Steps and Features

Data Loading The dataset is read directly from a GitHub URL in CSV format.
It contains 100 student records with attributes such as name, age, gender, country, school, and academic scores.

Data Exploration Displays all student records and column names.
Columns include:

StudentID, Name, Country, Gender, Age

Math_Score, Reading_Score, Writing_Score

School, Class

Feature Engineering Adds a new column: total_score, which is the sum of Math, Reading, and Writing scores.
Computes percentage_score based on a maximum of 300 points, rounded to two decimal places.

Assigns a Status of "Passed" or "Failed" based on whether the percentage is 50 or above.

Visualization Uses Seaborn and Matplotlib to plot a box plot of Math scores categorized by gender, revealing performance trends across sexes.

Data Cleaning and Renaming Renames Math_Score to Mathematics_Score and Gender to Sex for clarity.

Drops the School column to simplify the dataset.

Saving Processed Data The modified DataFrame is exported to multiple formats:
CSV: student_result.csv

Excel: my_excel.xlsm

You can also export it to SQL, JSON, or HTML if needed.

🔍 Final Outcome The dataset now contains:

Cleaned and enriched information.

Added insights through total_score, percentage_score, and Status.

Visualization that helps to understand the gender-wise distribution in Math performance.

Data ready for reporting or further machine learning tasks.
