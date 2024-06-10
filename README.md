NETFLIX DATA ANALYSIS PROJECT
Contents
(1) Dataset Description
(2) Usage
(3) Understanding the Dataset
(4) EDA Question
(5) Data Wrangling
(6) Data Cleaning
(7) Data Visualization
(8) Conclusions and Insights
(9) Built With

Dataset Description:
This dataset contains information about +8000 movies & TV Shows. Netflix is one of the most popular media and video streaming platforms,as of mid 2021, they have over 222M Subscribers globally. This tabular dataset consists of listings of all the movies and TV Shows available on Netflix ,along with details such as- cast, director,rating,release year,duration,etc.

The analysis covers various aspects of the dataset, including data cleaning, exploratory data analysis, and data visualization. It provides insights into the distribution of content, ratings, genres, countries, and other factors within the Netflix library.


Usage
(1) Download the Netflix dataset (netflix.csv) and place it in the same directory as the Python script.

(2) Open the Python script in a suitable environment (e.g., Google Colab, Jupyter Notebook or any Python IDE).

(3) Run the script. It will load and analyze the Netflix data, generating various visualizations and insights.

(4) Explore the generated plots and insights to gain a better understanding of the Netflix dataset.


Understanding the Dataset:

EDA Questions:
Q1. For "House of Cards", what is the show ID and who is the director of this show?

Q2. In which year the highest number of movies and TV shows were released? w/Bar graph

Q3.How many movies& TV shows are in this dataset?

Q4. Show all the movies that were released in 2021

Q5. Show only the Title of all TV shows that were released in United States only

Q6. Top 15 countries on Netflix based on amount of content

Q7. Show Top 10 Directors who gave the highest number of TV shows& Movies to Netflix

Q8. Show all the Records, where "type is TV Show and listed_in is British TV Shows" or "Country is United Kingdom".

Q9. In how many movies/shows, Tom Cuise was cast?

Q10. What are the different Ratings defined by Netflix?

Q11. What is the maximum duration of a movie/tv show on Netflix?

Q12. Which individual country has the Highest No. of TV Shows?

Q13. How can we sort the dataset by Year?

Q14. Find all the instances where:type is 'movie' and listed_in is 'Dramas'or type is'TV Show'& listed_in is 'Kids''TV'


Data Wrangling:
Our data can be found on netflix_titles.csv file provided on this repository, downloaded from Kaggle.



Data Cleaning:
(1) Deleting redundant columns.

(2) Dropping duplicates.

(3) Cleaning individual columns.

(4) Remove the Nan values from the Dataset.

(5) Some Transformations.

This tabular dataset consists of listings of all the movies and TV shows available on Netflix, along with details such as- cast, directors, ratings, release year, duration,etc.I have cleaned this dataset using Python, and the code can be found on the repository.



Data Visualization:
Using Matplotlib and Seaborn, we made several meaningful visuals and charts to help us gain informative insights regarding any correlation between attributes in our dataset, that'll be discussed in the next section.



Conclusions and Insights:
(1) The number of movies and TV shows on Netflix has been steadily increasing until 2019, but there was a decrease in content in 2020. This decline might be due to the COVID-19 pandemic, which likely affected the production and availability of new content during that year.

(2) The dataset consists of a total of 8807 content items,with 6,131 movies and 2,676 TV Shows.Each year,the dataset consistently exhibits a higher count of movies compared to TV Shows except 2021.

(3) The United States has the most content on Netflix, followed by India in second place and the United Kingdom in third place.In terms of quantity, the United States takes the lead on Netflix with over 3,000 content items emphasizing its dominant position.In contrast,India two countries when it comes to the number of content on Netflix.

(4) There are several Asian countries that rank prominently. This indicates a growing trend of anime and K-drama on Netflix,reflecting their popularity among viewers.

(5) The most common rating on Netflix is "TV-MA",This indicates that there is a higher proportion of content targeted toward mature audiences rather than younger viewers.

(6) We discovered that the longest content on Netflix has a duration of 312 minutes.

(6) The majority of null values in the dataset are found in the director column.

(7) The United States has the highest number of TV Shows, as they occupy the first position in "Top 15 Countries on Netflix" graph



Built With
. Google Colab

. Pandas

. Numpy

. Matplotlib

. Seaborn

Double-click (or enter) to edit











