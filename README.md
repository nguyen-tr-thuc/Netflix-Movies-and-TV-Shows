
</p>
<h1 align="center"> Netflix Movies and TV Shows </h1>

<h5 align="center"> This project is a part of "Data Science” curriculum as capstone projects at<a href="[https://www.almabetter.com/](https://www.coderschool.vn/vi)"> Coderschool </a> </h5>

## Objectives:<br>
* Conduct Exploratory Data Analysis.
* Try understanding what type content is available in different countries.
* Check if Netflix is increasingly focusing on TV rather than movies in recent years.



## Libraries utilized:<br>
* NumPy and Pandas - For dataset cleaning and analysis.
* Matplotlib, Plotly and Seaborn - For Data Visualization.
* SkLearn  -  For machine learning.
 

## Dataset used:<br>
This dataset from Kaggle, consists of tv shows and movies available on Netflix as of 2019.<br>
It is collected from Flixable which is a third-party Netflix search engine.
``` 
Attribute Information:

show_id : Unique ID for every Movie / Tv Show
type : Identifier - A Movie or TV Show
title : Title of the Movie / Tv Show
director : Director of the Movie
cast : Actors involved in the movie / show
country : Country where the movie / show was produced
date_added : Date it was added on Netflix
release_year : Actual Releaseyear of the movie / show
rating : TV Rating of the movie / show
duration : Total Duration - in minutes or number of seasons
listed_in : Genere
description: The Summary description
```
## Project overview:<br>
<p>Netflix, is an American subscription streaming service and production company. It was founded in 1997 by Reed Hastings and Marc Randolph in Scott’s Valley, California.</p>
<p>It offers a library of films and television series through distribution deals as well as its own productions, known as Netflix Originals.</p>

<p>Our objective is to conduct an Exploratory Data Analysis to understand what content is available in different countries and if Netflix has been increasingly focusing on TV rather than movies in recent years. And use these insights to cluster similar content by matching text-based features.</p>

<p>After loading the data, we start by observing the first and last five values to understand the dataset.
Next, we treat the null values by dropping them if the respective variables contain <1% of null values. This is followed by feature engineering to extract new variables from the datetime variable date_added.</p>
 
## Data Cleaning
In the initial data preparation phase,I performed the following tasks : 
1. Data loading and inspectation
2. Handling missing values
3. Data cleaning and formatting

 ## Exporatory Data Analysis
<p>This cleaned data is then used to conduct EDA in order to understand it better and identify the underlying trends.</p>
Exploratory Data Analysis (EDA) is crucial for understanding the Netflix dataset, uncovering patterns, trends, and insights. In this section, I explore various aspects of the dataset to gain a comprehensive understanding of the content available on Netflix, addressing key questions:

1. **Release Trends Over the Years:**
   - In which year did the highest number of TV shows and movies release? (Visualized using a Bar Graph)

2. **Movies and TV Shows:**
   - Show all records where the category is "Movie" and type is "Comedians" or the country is "United Kingdom." (Visualized using a Bar Graph)

3. **Different Ratings Defined by Netflix:**
   - What are the different ratings defined by Netflix?
## Data Visualization, Recommendations, Clustering using K-means ,Sentiment Analysis:<br>


<p>Once obtained the required insights from the EDA, we start with Pre-processing the text data by removing the punctuation, and stop words.</p>
<p>We will apply Principle Component Analysis to our data and select components, use K-means Clustering to group similar data. To select the best value of clusters, utilize the Silhouette score and Elbow Method.</p>
<p> Using the given data a simple recommender system was created using cosine_similarity and recommendations for Movies and Tv Shows were obtained </p>
<p>Sentiment Analysis on IMDB reviews Sentiment Analysis is widely used to find the opinion of the customers such as reviews, survey responses in websites or social media. Since the customers are expressing their thoughts, feelings and opinions more openly than ever before, sentiment analysis is becoming an essential tool to monitor and understand that sentiment in their reviews, comments, feedback etc.</p>

