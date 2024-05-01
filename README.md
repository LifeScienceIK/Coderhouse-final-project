# Tastes on Netflix
## Project description
I worked on this project as part of the data science course I took at Coderhouse. I went through the main stages of a data science lifecycle, including dataset description, the analysis of the commercial context, exploratory data analysis and the building of a ML model.

The analysed dataset was put together in 2021. That should be kept in mind when considering the conclusions I arrived at.

As the project was carried through for an Argentine learning platform, the comments in the code are written in Spanish whereas the presentation of the project is available in Spanish and English.
## Tasks completed
I cleaned and analysed a dataset containing information on the popularity and features of different kinds of Netflix content.

* I first identified the columns that will be of no interest for the analysis and found ways to eliminate null values depending on each particular case.
* Through exploratory data analysis, I was able to identify the most common types of content as well as the features, such as genre, origin country and release year, that can contribute to the popularity of content
* To build an effective ML model, I created new variables by combining the values from other columns. Namely, I calculated the total runtime of each content item as well as the time period it belongs to.
* I compared several clustering algorithms to select the most suited one based on various metrics, including the Silhouette score and Davies-Bouldin score. I then trained a KMeans model that divided the data into 15 clusters.
* The three clusters having the highest average popularity were analysed in detail and several promising types of content were identified.
* I used the Nearest Neighbors algorithms to create a function that makes content suggestions for users based on a content item they liked.
## Results
With the help of the exploratory data analysis and clustering model, I identified particular features that make a content item more likely to become popular. Thus, the most popular types of content on the platform seem to be crime drama movies, comedy movies and TV shows as well as Japanese animes.

The suggestion fuction, in turn, manages to pick out relevant content items that coincide in the language, genre and production country with the item liked by the user.
