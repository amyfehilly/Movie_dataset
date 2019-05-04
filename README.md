# Movie_dataset
Exploring a movie data set and its variables
Investigate a movie dataset - This data set contains information of about 10,000 movies collected from The Movie Database (TMDb), 
including user ratings and revenue.
The data can be found here: 
https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv&sa=D&ust=
1532469042115000

This dataset is being explored to see how the movie industry has been affected over time. 
The independant variables are revenue and runtime. I hope to learn how over time movie trends have changed and if there is any 
correlation with the independant variables over time.The main questions being asked are:
1) How have revenues (adjusted for inflation) been affected over time?
2) How have movie runtimes been affected over time?

The dataset was pulled in and assessed visually and programatically before cleaning it. There is some missing data in the dataset. 
Members of the cast, imdb_id, director, genres all have missing data. Because none of this data is numberic and cannot be replace by a 
mean, and because the quantities are low, I decided to drop those missing values in the cleaning of the data.

Revenues: In summary we see that although more movies are being made over time, the accumulative revenues are dropping. 
Limitations to this conclusion are the missing and null values which I removed from the data set in order to make the analysis easier.
Run Time: Movie runtimes have decreased over time. This is important as it shows a change in movie length trends. 
There is an increase in short films, and extremely long films but the general trend shows that runtimes are being reduced. 
This finding could be limited in that null and missing values were removed in order to analyse the data.
