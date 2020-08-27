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

## Budget vs. Profit

![alt text](Images/Production%20Budget%20vs%20Worldwide%20Gross.png)

The above graph shows the relationship between the budget(1e8) in dollars vs the worldwide gross revenue(1e9) in dollars, in the past 10 years. We can see a positive correlation. However, calculating profit, the budget minus the gross revenue, will give more information.

![alt text](Images/Production%20Budget%20vs%20Profit.png)

The above graph shows the relationship between the budget(1e8) in dollars vs the profit(1e9) in dollars, in the past 10 years. We can still see a positive correlation, though not as significant. 

![alt text](Images/Budget%20distribution.png)
![alt text](Images/Profit%20distribution.png)

The above graphs show the distributions of budgets and profits. The curves are positively skewed and are affected by large outliers. The median should give more accurate numbers than the mean due to the outliers. The median budget is $16,900,000 and the median profit is $8,366,398.

## Genres vs. Popularity 

Genres vs Popularity 1
![alt text](Images/Genres%201%20-6.png)
                    Genres vs. Popularity 2
![alt text](Images/Genres%207-12.png)
                    Genres vs. Popularity 3
![alt text](Images/Genres%2013-19.png)

The above boxplots show the distribution of popularity scores for each genre. Every movie has a popularity score and genre, or multiple genres, these boxplots show the popularity score correlated to the movie where that the genre is present. We can see that Adventure and Action are the genres with the highest popularity.

# Conclusions and Recommendations 
1. Runtime does not significantly impact average rating, though outliers indicate that if a movie is longer the average rating is often high. The recommendation is to aim for a runtime around the median runtime, 87 minutes, however if the film is longer, it should not be negatively impacted. 
2. There is a positive correlation between budget and worldwide gross revenue. There is also a positive correlation between budget and profit, although not as steep. Unfortunately some data for worldwide gross revenue was 0, which effects exact number recommendations. Profit does generally increase as budget increases. 
3. Action and Adventure were two genres that were included in movies with the highest general popularity. Other popular genres include, Crime, Thriller, and Science Fiction. The recommendation is to include at least one of these genres in the film, especially Action or Adventure. 
