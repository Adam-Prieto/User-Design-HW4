# Assignment 4: Information Visualization

### Adam Prieto and Filip Casey
### Dr. David Quigley
### 19 November 2024
### User Centered Design I


## Background

For this assignment, we decided to analyze the "World Happiness Report" data set and see if we could gain any meaningful insights from the provided data. That said, here is our assignment. 

## User Questions - Adam

1.) I think that countries with higher levels of corruption would be ranked lower on the Social Development Ladder as a direct result of the government's incompetence and unwillingness to get things done. That said, I think that there would be a negative relationship between Corruption and Social Development (as corruption increases, social development decreases).

2.) As an inverse to my previous question, I think that Generosity and Life Expectancy would have a positive relationship since generous people would have less to think about and more social help from their peers, which would result in the aforementioned positive relationship. 

## Required Data and Comparisons - Adam

For my first user question, I would need to gather all of the non-null Corruption and SD Ladder data from the dataset, map the results in a scatter plot, and then mathematically calculate the correlation coefficient from the resulting data. Then, using human inference, I would need to determine if the corresponding graph and coefficient value map that of my first user question (does a negative correlation exist). If so, then my idea is worthy of further consideration and vice versa. 

For my second user question, I would follow all of the steps from my previous user question, but tweak the results to match a positive correlation -- that is, do the data points in my graph follow a steadily increasing, non-pleatuing, relationship in the graph and does a value greater than 0 (and preferably over 0.5) result from the data trend? 

## User Questions - Filip

1. Given that some countries with lower GDPs are ranked higher on the Cantril Ladder than those with higher ones, what
contributes to the happiness of people in those countries instead?
2. In countries with highly variable Cantril Ladder score, are social or governmental factors more impactful on the
level of happiness?

## Required Data and Comparisons - Filip

1. To keep things simple, I will consider countries with "low" GDP to be those that are in the bottom 50th percentile
   (their rank is lower than 77), once filtered by that I will rank the rest of the features by which have the highest
    average ranking, as this will provide me information on which generally contribute more towards the Cantril Ladder 
    score. For the top three features I will provide 2 scatter plots relating the Cantril Ladder score and the feature 
    for 1. all countries and 2. the subset of countries with lower GDPs. This will provide a generally good qualitative
    analysis of the difference between the two.
2. In answering this question I will use a similar methodology. A highly variable Cantril Ladder score will be defined
    as one that is in the top 50th percentile (higher than 77). Instead of evaluating all features this time I will only
    be comparing social support and generosity (for social) and freedom and corruption (for governmental). I will use 
    the same average rank strategy, as this still provides an indication as to which feature is more impactful. I will
    also include a scatter plot showing the relationship between the Cantril Ladder SD and average of social factors 
    and governmental factors to see if a relationship is clearly portrayed there. I will also plot a map of the world
    coloring which factor is more influential to see if geography plays some role in this preference.