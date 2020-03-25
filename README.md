# Module 1 Final Project

## The Project

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry.
Your team is charged with doing data analysis and creating a presentation that explores what type of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the CEO can use when deciding what type of films they should be creating.

# The Dataset

For this project some movie-related data was provided from :
* Box Office Mojo
* IMDB
* Rotten Tomatoes
* TheMovieDB.org

# My Approach
* Use `pandas` to initially ingest the datasets
* Explore foreign key relationships between datasets to join tables
* Use `pandasql.sqldf` to use SQL to join dataframes
* Use `pandas` to clean columns, convert incorrect column types, add new calculated columns
* Use `seaborn` to visualize data

# Questions answered

## How many films are actually profitable?
![graph_1](img/graph_1.png)

The vast majority of films in our dataset were profitable. We can reasonably expect to make money in this new venture assuming our firm performs as well as the average firm. The mean profit margin for films was 39%.

## Which directors have the most profitable films?
![graph_2](img/graph_2.png)

The top 3 directors by average total_profit are Adam Green, Kyle Balda, and Joss Whedon.

## When is the best time of year to release a movie?
![graph_3](img/graph_3.png)

According to the graph the best time to release a movie with regard to gross margin would be in the months of July, January, or November. One caveat: the difference between high gross margin months and low is so miniscule that release_month may not be a statistically significant variable. Other variables like, the quality of the film, the popularity of the cast and directors will probably affect the gross margins much more.

# Initial Recommendations:
* Hire Adam Green, Kyle Balda, or Joss Whedon because of their history of profitable films.
* Plan the production schedule for a release in the summer, preferably in July.
