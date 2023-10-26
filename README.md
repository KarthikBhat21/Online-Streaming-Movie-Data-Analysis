# Online-Streaming-Movie-Data-Visualization
Python, Kafka, MongoDB, Tableau


## Data source: TMDB 
TMDB is the collaborative database regarding movies and TV shows.
It contains more than 5000 movies and other information such as Cast, Crew, Budget, Profit/Loss incurred, Genre, Movie Language., etc.


## Pipeline

1. The data collection was made by making use of TMDB API using Python and pushed to Apache Kafka.
2. The data was then pushed to MongoDB database using Kafka connector.
3. Data Visualization was performed using Jupyter Notebook.

![image](https://github.com/KarthikBhat21/Online-Streaming-Movie-Data-Visualization/blob/main/ETL%20pipeline.jpg?raw=true)

## Visualization and Analysis

1. Based on the analysis, we can say that among various genres, the viewers like to watch more drama based movies.

![image](https://github.com/KarthikBhat21/Online-Streaming-Movie-Data-Visualization/blob/main/Movie%20Popularity%20w.r.t%20Genre.PNG?raw=true)

2. Year wise Movies revenue.

![image](https://github.com/KarthikBhat21/Online-Streaming-Movie-Data-Visualization/blob/main/Movie%20Revenue%20w.r.t%20year.PNG?raw=true)

3. As we know, a story is really important in a movie. But how that story is portrayed to the users matters the most. So, the higher the budget of the movie, the higher the revenue will be which is exactly shown in the below visual.

![image](https://github.com/KarthikBhat21/Online-Streaming-Movie-Data-Visualization/blob/main/Movie%20Budget%20vs%20Revenue.PNG?raw=true)
