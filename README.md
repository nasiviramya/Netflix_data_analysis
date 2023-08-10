# Netflix_data_analysis
Netflix data analysis involves the process of collecting, processing, and interpreting various types of data related to the streaming platform Netflix.
The project involves various data manipulation and analysis techniques to answer specific questions about the dataset. 

**Data Exploration and Cleaning:**
1. Remove duplicate records from the dataset.
2. Identify and visualize null values using a heatmap.

**Specific Questions and Tasks:**
1. Identify the show ID and director of the show 'House of Cards'.
2. Create a bar graph to show the year with the highest number of TV shows and movies released.
3. Create a bar graph to display the count of movies and TV shows in the dataset.
4. Display movies released in the year 2000.
5. Display titles of TV shows released in India.
6. Identify the top 10 directors with the highest number of TV shows and movies.
7. Display records where the category is 'Movie' and the type is 'Comedies', or the country is 'United Kingdom'.
8. Determine how many movies/shows Tom Cruise was cast in.
9. Identify different ratings defined by Netflix.
    a. Count movies with 'TV-14' rating in Canada.
    b. Count TV shows with 'R' rating after the year 2018.
10. Determine the maximum duration of a movie/show on Netflix.
11. Identify the country with the highest number of TV shows.
12. Sort the dataset by year.
13. Find instances where:
    - Category is 'Movie' and type is 'Dramas', or
    - Category is 'TV Show' and type is 'Kids' TV.

**Python Techniques Demonstrated:**
- Data exploration using `head()`, `tail()`, `shape`, `info()`, `value_counts()`, `unique()`, etc.
- Data cleaning using `dropna()`, `isnull()`, and `duplicated()`.
- Filtering data using boolean conditions and logical operators (`and`, `or`).
- Data visualization using `sns.countplot()` from the Seaborn library for bar graphs.
- Basic descriptive statistics using `max()`, `min()`, `mean()`.
- Manipulation of datetime data using `to_datetime()` and `dt.year`.

This project is a practical example of data analysis using Python, where you perform data cleaning, exploration, and visualization to answer specific 
questions and gain insights from a dataset.
It covers a range of data analysis techniques commonly used in data science projects.
