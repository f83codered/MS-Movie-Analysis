# Microsoft Movie Analysis

**Author**: Filippe Fontenele

## Overview

Microsoft wants to compete in the movie production business and want help to decide which genres are doing well. This project uses two different datasets from the IMDb site to gain insight in which group of genres would help the company starts its new studio with the right foot. Also used a data set from the website The Numbers to find profitable genres and movies. After cleaning, merging and analysing the data, I reached the conclusion that the Action, Adventure, Sci-Fi genres would be a safe and profitable bet for Microsoft to begin with but also reached the conclusions that not all films that had high budgets were profitable and that public perception doesn't necessarily mean a movie will fail.

***

## Business Problem

Microsoft is a giant that wants to venture into a new business to make profit. We used two datasets to give us an insight into public opinion and another to give us an overvew of financial success.

***

## Data

Two datasets came from IMDb website, a famous online database for information on movies, TV shows and entertainment. My main focus with this data is the insight into public perception of movies and the easy I'd have to merge data afterwards. I also used a dataset from the website The Numbers, a website that focuses on providing detailed financial analysis and box office reports for movies, offering insights into the financial performance of films in the entertainment industry.
 

***

## Methods

After inspecting the information on each column, I used the 't_const' to merge the rating and basic dataframes, since it was the unique identifier between them, creating a new dataframe called merge. After renaming the 'movie' column, I joined the profit dataframe through the 'primary_title' column, now common on both data frames, giving birth to profit_merge.


Checking the information on the new dataframe, I decided dropping more columns ('original_title', 'id', 'release_date') and using only the last 10 years of information. From this, I had the finaldf, that I now decided to fill the null values. After that I created three new datasets called critically_aclaimed, most_profitable and success_groupto analyse public perception about movies and relation between average rating x ROI.

***

## Results


3 graphs show clearly that Action, Adventure, Sci-Fi are the best bet for Microsoft as a first genre of movie. It is a growing trend that can be explored especially if the company can look inwards at its rich history or at its games division.


***

***



## Conclusions

This analysis lead to a few recommendations of genres and future steps.

Microsoft should start its life in the movie business by producing an Action, Adventure, Sci-Fi film since it is consistent as a success with the public, scoring high ratings in the IMDb website, and very profitable.
Results vary once outside this genre but if the company wants other alternatives that will lead to profits and public approval, I can recommend Biography, Comedy, Drama or Action, Adventure, Biography.

Although our finds show there is a weak correlation between budget and profits, a deeper analysis into how to sctructure budget is needed.

***