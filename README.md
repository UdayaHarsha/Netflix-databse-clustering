# Netflix-Movies-and-TV-Shows-Clustering

## Context:
This dataset consists of tv shows and movies available on Netflix as of 2019. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

## Object :
This project aims to classify and group Netflix shows into specific clusters in such a way that shows in the same cluster are similar to one another and shows in different clusters are different.

## Description:
Show_id : Unique ID for every Movie / Tv Show

Type : Identifier - A Movie or TV Show

Title : Title of the Movie / Tv Show

Director : Director of the Movie

Cast : Actors involved in the movie / show

Country : Country where the movie / show was produced

Date_added : Date it was added on Netflix

Release_year : Actual Releaseyear of the movie / show

Rating : TV Rating of the movie / show

Duration : Total Duration - in minutes or number of seasons

Listed_in : Genere

Description: The Summary description

## Conclusion:
In this project, we tackled a text clustering issue where we had to categorize Netflix shows into specific clusters such that the shows within a cluster are similar to one another and the shows in different clusters are dissimilar to one another.

We delt with missing values and duplicated values in the data.

we see that the movies are more than the the tv shows in the data.

We check top 10 in all the columns.

We see that the movies and tv shows are released more in december. and views prefer more Tv-MA rating for both Tv shows and movies.

The TFIDF vectorizer was used to tokenize, preprocess, and vectorize the values in these attributes. 10000 attributes in total were created by TFIDF vectorization.

The problem of dimensionality was dealt with through the use of Principal Component Analysis (PCA).

Utilizing the K-Means Clustering algorithm, we first constructed clusters, and the optimal number of clusters was determined to be 6. The elbow method and Silhouette score analysis were used to get this.

The Agglomerative clustering algorithm was then used to create clusters, and the optimal number of clusters was determined to be 4. This was obtained after visualizing the dendrogram.

