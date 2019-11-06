# TMDB_dataset_analysis
This is a project using TMDb dataset from kaggle. The dataset will be gathered, cleaned, restored and analyzed for result. In this project, we are most interested in what variables will be highly impact on movie revenue and how these variables impact the revenue from overall view and answer the following questions:
What is the relationship between movie's popularity and revenue?
What is the relationship between movie's budget and revenue?
Which director/cast will be more likely to have high revenue movie?
Which genres is considered "best" for movie revenue? And which genres are considered "worst" for movie revenue?

# Dataset Overview:
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.
Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
There are some odd characters in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is.
The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.
Resource: https://www.kaggle.com/tmdb/tmdb-movie-metadata

# Conclusion after analysis:
In a word, "budget" ,"popularity" and "vote_counts" are positivly correlated with movie "revenue".
Great director has positive relationship with movie revenue. Although top directors not always guarntee highest average movie reveue. The only director has both higher total movie revenue and higher average movie revenue is David Yates.
Cast has no obvious impact on movie revenue.
The top genre for movie revenue is adventure, and the botton genre for movie revenue is TV movie.
