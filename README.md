# Movie Analysis Project

This movie analysis will investigate the following questions:

1. Does movie runtime impact the rating of the movie, is there an ideal runtime?

2. What is a suggested budget and how does it affect profit?

3. How does genre affect popularity?

Tools used:
    
    Jupyter Notebook(Python)
    Matplotlib
    Seaborn

The data used in this analysis is from IMDB and TMDB provided by Flatiron School

# The Analysis
## Runtime vs. Average Rating 

![alt text](/Images/Runtime%20vs%20Rating.png 'With Outliers')




![alt text](/Images/Runtime%20VS%20Rating%20no%20outliers.png "Without Outliers")

![alt text](/Images/Runtime%20minutes%20distribution.png)

The above graphs show that there is not a strong correlation between runtime and the average rating. However, the outliers show that an extra long runtime may not negatively affect the rating. The median runtime, as seen in the distrubtion graph, is 87 minutes. 

![alt text](Images/average%20rating%20mean%20vs%20runtime%20minutes%20ranges.png)

The above graph indicate that if a movie is extremely long or very short the average rating may be higher than movies of average length.

![alt text](/Images/Number%20of%20Movies%20vs%20Runtime%20Minutes%20Ranges.png)

 However, the number of movies in each runtime range affects the average rating mean across each group of runtimes.

## Budget vs. Profit

![alt text](Images/Production%20Budget%20vs%20Worldwide%20Gross%20regplot.png)

The above graph shows the relationship between the in dollars vs the worldwide gross in dollars, in the past 10 years. We can see a positive correlation. However, calculating profit, the budget minus the gross revenue, will give more information.

![alt text](Images/Production%20Budget%20vs%20Profit%20regplot.png)

The above graph shows the relationship between the budget in dollars vs the profit in dollars, in the past 10 years. We can still see a positive correlation, though not as significant. 

![alt text](Images/Budget%20distribution.png)
![alt text](Images/Profit%20distribution.png)

The average budget is $36.5 million. The median is $16.9 million, so half of the movies in this data fall below a budget of $16.9 million.
The Budget and the Profit distributions are positively skewed so the mean is affected by the higher outliers and is much greater than the median.

## Genres vs. Popularity 

Genres vs Popularity 1
![alt text](Images/Genres%201%20-6.png)
                    Genres vs. Popularity 2
![alt text](Images/Genres%207-12.png)
                    Genres vs. Popularity 3
![alt text](Images/Genres%2013-19.png)

The above boxplots show the distribution of popularity scores for each genre. Every movie has a popularity score and genre, or multiple genres, these boxplots show the popularity score correlated to the movie where that genre is present. We can see that Adventure and Action are the genres with the highest popularity.

# Conclusions and Recommendations 
1. Runtime does not significantly impact average rating, though outliers in this data set indicate that if a movie is extremely long or very short the average rating may be higher than movies of average length. However, the number of movies with 0-30 minutes runtime is significantly lower than movies with 60-90 or 90-120 minutes. More analysis is needed to give a specific recommendation for runtime.
2. There is a positive correlation between budget and worldwide gross revenue. There is also a positive correlation between budget and profit, although not as steep. Unfortunately some data for worldwide gross revenue was 0, which effects exact number recommendations. Profit generally increases as budget increases. The standard deviation of the movie budgets is $51,544,150. There is about $50,000,000 of room for the budget to deviate (positively) from the average of $36,533,470 to adjust the budget for the production’s specific needs.

3. Action and Adventure were two genres that were included in movies with the highest general popularity. Other popular genres include, Crime, Thriller, and Science Fiction. The recommendation is to include at least one of these genres in the film, especially Action or Adventure. 
