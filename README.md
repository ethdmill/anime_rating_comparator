**Welcome to the Anime Rating Comparator!**

To view the project within this repo, click on "anime_rating_comparator.ipynb" above!

This project answers the question of whether or not the user rating of an anime title and the number of users who voted on it affect each other in any kind of correlatable ways. It also takes a look at the highest averages of user rating and number of user votes by title type. These questions are applicable to all media, especially from a sociological perspective, but for purposes of this project, I stuck to anime to keep things deliberate and focused.

I accomplished this by importing a large data set from Kaggle that aggregates user data from a website called myanimelist.net, a very prominent website in the anime community. To keep the datasets below R-Rated and as free of outliers as possible, I omitted the strictly adult content from the main dataset, which proved to be very useful.

I analyzed the data through a combination of scatter plots and averages, all using SQL queries and matplotlib functions. I chose to display each set of data in easily digestible, yet still distinct ways - hence only displaying the top five rows for each presented data set and ordering them by different columns.

As far as the scatter plots go, I found that using a logarithmic scale on the y-axis, as mentioned in the project markdown, drastically helped to accentuate and correlations and trends in the data, and also to make the plots more generally readable, as each plot contains thousands of data points.

I originally planned to incorporate a potential correlation analysis between TV Series Rating and TV Series Episode Count, but found that many of the TV Series episode data were incomplete, even for famous shows. To my knowledge, the data also did not include shows that are still airing, marking their episode counts as "unknown". Thus, no conclusive analysis of that trend is possible at this time.

There is nothing too specifically unique about the terminology used in the project (besides OVA, for instance, which simply stands for Original Video Animation), and the markdown explains each step along the way. As such, there are also no special dependencies necessary to run the project outside of Anaconda and Jupyter Notebooks, though the project is viewable in its entirety online via its Github repository.

Thank you for checking out my project!


-- Ethan Miller
