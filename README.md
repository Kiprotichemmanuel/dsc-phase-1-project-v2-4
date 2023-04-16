# Phase 1 Project Description

Microsoft Movie Studio
Authors: Kiprotich Emmanuel

Overview
This repo helps to explore relationships between runtime, budget, genre and ROI. The best movies for optimizing ROI are comedy, musical romance, drama and performing arts. These tend to have higher votes_average and popularity.The best movies for optimizing vote score and total profit are played for long, high budget it include comedy, drama, romance and performing arts. in order to achive high ROI the company must also focus on other factors like promotional activities, quality production and content creation.
Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They havedecided to create a new movie studio, but the problem is they don’t know anything about creating movies. Theyhave hired you to help them better understand the movie industry. Your team is charged with exploring what type offilms are currently doing the best at the box office. You must then translate those findings into actionable insightsthat the head of Microsoft's new movie studio can use to help decide what type of films to create

Questions to consider:

1.Which genre types are most likely to be received by the audience?
2.What are the most sucessful distribution channel for movies?
3.Which genre combination have the highest return on investment?

Data Understanding
In the folder zippedData in the associated GitHub repository are movie datasets from:

Box Office Mojo
IMDB
Rotten Tomatoes
TheMovieDB.org
Questions to consider:

1.Which genre types are most likely to be received by the audience?
What do the data represent? Who is in the sample and what variables are included?
What is the target variable?
ROI, profit, and vote_average.
What are the properties of the variables you intend to use?
Methods
Describe and justify the process for analyzing or modeling the data.

Questions to consider:

How did you analyze or model the data?
Perform regressions on ROI vs genre, runtime, and budget, identify the optimal choices, and repeat using other metrics until we come to a full recommendation on what type of move to make.
How did you iterate on your initial approach to make it better?
We examined many different slices of the data and visualizations until we found significant results. Discovering and fixing data cleaning and quality issues ended up changing our results significantly from the start to the end of the analysis process, so it's hard to say what modelling changes had a large impact.
Why are these choices appropriate given the data and the business problem?
Microsoft has a lot of capital, but also lots of other expenses. We analyzed the data with multiple target variables in mind to enable them to make a good decision no matter how much capital they want to invest, how profitable their other investment opportunities are, or how much they think their movie studio's brand might influence the "Microsoft" brand (for better or worse).
Evaluation
Evaluate how well your work solves the stated business problem.

Questions to consider:

How do you interpret the results?
We identified movie types that vastly outperform average movies on all key metrics, which is a great result for shaping studio policy.
How well does your model fit your data? How much better is this than your baseline model?
We don't have real "models" yet. Summary statistics indicate our recommendations should increase expected profit, ROI, and vote average beyond making generic movie.
How confident are you that your results would generalize beyond the data you have?
Very confident.
How confident are you that this model would benefit the business if put into use?
Very confident.
Conclusions
Provide your conclusions about the work you've done, including any limitations or next steps.

Questions to consider: *“Middle of the Road” movies are the worst across all metrics: ** Make a low-budget (for best ROI) or high budget (for best profit, best ratings, good ROI) movie, not a middle budget movie ** Make a movie that is either long or short, not medium length

Pick Genre that suits budget and length:
Horror/Thriller for Low Budget/Short Movies
Sci-Fi/Thriller for High Budget/Long Movies
Intellectual Property seems important for successful High Budget/Long Movies
We did not fully explore this relationship due to limited data about IP costs; would recommend obtaining this data and re-analyzing
Acquire movie rights for comic book superheroes or popular books.
Further Research
We can help analyze directors/writers/actors within a certain genre/budget/runtime once you make a decision!
For More Information
Please review our full analysis in our Jupyter Notebook or our presentation.

