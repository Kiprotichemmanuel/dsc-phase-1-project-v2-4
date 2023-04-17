# Phase 1 Project Description

Microsoft Movie Studio
Authors: Kiprotich Emmanuel

Overview
This repo helps to explore relationships between runtime, budget, genre and ROI. The best movies for optimizing ROI are comedy, musical romance, drama and performing arts. These tend to have higher votes_average and popularity.The best movies for optimizing vote score and total profit are played for long, high budget it include comedy, drama, romance and performing arts. in order to achive high ROI the company must also focus on other factors like promotional activities, quality production and content creation.
Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They havedecided to create a new movie studio, but the problem is they don’t know anything about creating movies. Theyhave hired you to help them better understand the movie industry. Your team is charged with exploring what type offilms are currently doing the best at the box office. You must then translate those findings into actionable insightsthat the head of Microsoft's new movie studio can use to help decide what type of films to create

Variables:
This project focus on below indepent variables
* Revenue
* marketing
* genre

Questions to consider:

1. Which genre types are most likely to be received by the audience?
2. What are the most sucessful distribution channel for movies?
3. Which genre combination have the highest return on investment?

# Data Understanding
In the folder zippedData in the associated GitHub repository are movie datasets from:

* Box Office Mojo
* IMDB
* Rotten Tomatoes
* TheMovieDB.org
# Data analysis

1. Which genre types are most likely to be received by the audience?
To answer the above question the project focused on;
Performing regressions on ROI vs genre, runtime, and budget, identify the optimal choices, and repeat using other metrics until we come to a full recommendation on what type of move to make.
How did you iterate on your initial approach to make it better?
We examined many different slices of the data and visualizations until we found significant results. Discovering and fixing data cleaning and quality issues ended up changing our results significantly from the start to the end of the analysis process, so it's hard to say what modelling changes had a large impact.
Why are these choices appropriate given the data and the business problem?
Microsoft has a lot of capital, but also lots of other expenses. We analyzed the data with multiple target variables in mind to enable them to make a good decision no matter how much capital they want to invest, how profitable their other investment opportunities are, or how much they think their movie studio's brand might influence the "Microsoft" brand (for better or worse).

2. What are the most sucessful distribution channel for movies?
To check on this aspect, the analysis focused on popularity and vote_average.
Summary statistics indicate our recommendations should increase expected profit, ROI, and vote average beyond making generic movie. increasing the popularity also wil translate to more votes. this increases the chances of improving the return on investment.this section regreted the two variables against ROI and perform correlation analysis which were also visualized to get clear understanding of the behaviour.

3. Which genre combination have the highest return on investment?
In this question the analysis focused on identifying genre combination with high returns on investment. after cleaning the data the analysis was done and visualized. this shows that the comedy, drama, performing arts, romance were aong the top performing movies. checking on the costing vs the return on investment show that there is negative correlation. This shows there are other factors to be considered in order to improve on the aspect of return on investment. Apllying appropriated promotional channel, quality issue and content creation are three issues to be put into consideration. 

# Project Conclusion
This project aimed to identify properties that are associated with movie popularity and provide recommendations to Microsoft Studios based on the analysis.

After cleaning and trimming the dataset, I created a secondary table that broke down each movie into the separate genres it falls under. I plotted various variables against vote average and found that movies with higher vote averages tend to have higher budgets and higher revenue. However, there was a weak correlation between popularity, vote average, and return on investment.

# Recommendations
Based on the analysis, I recommend the following to Microsoft Studios:

Release comedy, musical, performing arts, drama, and romance movies as they are highly captivating the population.
Invest more in the production of comedy, performing arts, musical, drama, and romance movies.
Commit more funds to promotional activities, quality, and content of movies being produced.
Overall, Microsoft Studios should focus on balancing all aspects, including quality, content, marketing strategies, and budget allocation, to improve the return on investment for their movies.presentation.

