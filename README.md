
# Netflix Shows and Movies clustering 

A brief description of what this project does and who it's for


## Objective 
1. Analyse Netflix TV shows and Movies data to get meaningfull insight 
2. Understand what type of content is available in different countries. 
3. On what contect Netflix is focusing more is it a TV shows or Movies ?
4. Perform EDA to establisih relationship in data. 
5. Use Unsupervised Machine Leanring clustering method to get cluster by similar text based feature 

## Problem statement 
The goal of this project is to find similarity within groups of people to build a movie recommendation system for users. We are going to analyze a dataset from the Netflix database to explore the characteristics that people share in movies. We have experienced it ourselves or have been in the room, the endless scrolling of selecting what to watch. Users spend more time deciding what to watch than watching their movie.
## Method Used 
1. Descriptive Statistics 
2. Data Visualization
3. Unsupervised Machine Learning 
## Libraries Used 
Numpy 
Pandas 
Matplotlib 
Plotly 
Sklearn 

## Data Set 
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

show_id : Unique ID for every Movie / Tv Show

type : Identifier - A Movie or TV Show

title : Title of the Movie / Tv Show

director : Director of the Movie

cast : Actors involved in the movie / show

country : Country where the movie / show was produced

date_added : Date it was added on Netflix

release_year : Actual Release Year of the movie / show

rating : TV Rating of the movie / show

duration : Total Duration - in minutes or number of seasons

listed_in : Genere

description: The Summary description
## Conclusion 
K-MEANS

From the elbow graph and silhouette analysis, the best model has a silhouette score of 0.49346 produced with 8 Clusters using K Means Algorithm The model also had a Davies-Bouding Index of 0.8395 and Calinski-Harbaz Score of 3353

Hierarchical Clustering

Using dendograms and comparing various distance thresholds, a distance of 20 produced the highest silhouette score of 0.495390 with 8 clusters The model also had a Davies-Bouding Index of 0.8295 and Calinski-Harbaz Score of 3352
