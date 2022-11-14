Movies: To Spend or Not To Spend

Does a movie's budget have an impact a movie's outcome, gross income or rating?

Questions needed to be answered to figure out if there is a relationship between a movie's gross income and that movie's production budget. These questions were developed to look directly at the budget vs income relationship, but also to look at other factors that may have an impact on a movie's income. The questions are below, along with the correlating notebook supporting the various analyses.

Is there a correlation between a movie's budget and the domestic/worldwide gross? (erics_movies.ipynb)

At first glance I believed the higher the movie budget, the more money it was going to make domestically and worldwide. However, the domestic r-squared value is .32, the worldwide r-squared value is slightly higher at .42 and the points on the scatter plot have a greater dispersion the higher the budget gets. I would say that a higher movie budget does not fit our assumption that the greater the budget the greater the profits.

Over the years how has a movie's budget changed, and has there been a correlating change in gross income, domestic and worldwide?
(pie_charts.ipynb)

All four categories have increased over time. The Average Production Budget was 5,000,000 in 1975 and over time increased to 210,000,000 in 2018 which equates to an approximate increase of 4,100%. The average domestic and worldwide gross were both approximately 42,000,000 dollars in 1975 and increased over time to approximately 472,000,000 and 1,197,100,00 in 2018, which reflected increases of approximately 1,028% and 2,762%. This data also illustrates that the average gross income of approximately 37,000,000 dollars in 1975 has increased to approximately 987,000,000 dollars in 2018, which equaled an increase of approximately 2,580%. The data reflects that over the years all categories did increase; however, the rate of increase varied. 

How does a production's budget breakdown per genre, and does the genre also have an impact on the worldwide or domestic gross?
(pie_charts.ipynb)

The data illustrates that the genre does directly impact the average production budget. The average production budget for Action movies was approximately 190,000,000 dollars per movie, which was approximately 50,000,000 dollars higher than the next highest category, which was Fantasy at approximately 140,000,000 dollars per movie. Additionally, the average Domestic Gross (377 mil) and Worldwide Gross (987 mil) is also the highest for Action movies. This is approximately 100,000,000 dollars domestically and 80,000,0000 dollars worldwide higher than the next highest genre's, which were Horror and Fantasy. This confirms that the genre does impact Domestic and Worldwide Gross. It was interesting to note that Walt Disney pictures had one of the highest production counts but also averaged the highest production budget per movie. This would lead you to assume that if we looked primarily at the Action genre, we should expect to see Walt Disney Picture with the highest count. Data proves this to be correct as Walt Disney has the highest amount of Action movies with a total count of seven and an overall highest average production budget per movie with an average of approximately 176,000,000 dollars per movie. 

Will a movie's production budget be reflected in the ratings of that movie? (budgetandratings.ipynb)

When reviewing the data, we initially wanted to identify the movies with the highest IMDB ratings and the ones with the lowest IMDB ratings and then compare how the budgets for each data set identified. Within the data compiled, there was 12 movies identified as having an IMDB rating of equal or greater than 8.3 and each movie had an average budget of roughly 140 million dollars. The highest rated movie per the data compiled was The Dark Knight which had a production budget of 185 million dollars and achieved a 9.0 IMDB rating.

Conversely there were 7 movies identified as having an IMDB rating equal or less than 5.5 and each movie had an average budget of roughly 84 million dollars. The lowest rated movie per the data complied was The Twilight Saga: New Moon, which had a production budget of 50 million dollars and achieved a 4.6 IMDB rating.

We then wanted to identify the movies with the highest and lowest production budgets and then compare how their IMDB ratings were. Within the data compiled, there were 12 movies identified as having a production budget of 230 million dollars or higher. Each movie had an average budget of roughly 281 million dollars and an average IMDB rating of 7.35. In terms of the lowest production budgets, there were 13 films identified as having a production budget of 12 million dollars or less. Each movie had an average budget of roughly 7.7 million dollars and an average IMDB rating of 7.08.

Based upon the information compiled we can confirm that there is a correlation with the production budget of a film and their ratings. An interesting observation was the highest budget film, Pirates of the Caribbean: On Stranger Tides had a production budget of 379 million dollars and only obtained a 6.7 IMDB rating; however, the lowest production budget film of The Full Monty obtained a 7.2 IMDB rating with a production budget of only 3.5 million dollars.

Does the director affect the gross outcome or does the budget? (directors.ipynb)
    
Based upon the analysis that was done it can be said that the number of movies that a director has done, or the director’s experience, does affect the gross domestic outcome more so than the production budget, but only to a point. That point happens to be when the average budget decreases and outweighs the director’s experience. The worldwide gross does not appear to be affected by a director's experience but does have the same result as the gross domestic. As the average budget decreases there is a higher likelihood of a high percent change. It is understandable for there to be a difference between the gross domestic and worldwide outcome. Majority of the movies and directors on this dataset are English speaking and/or American movies. On the domestic (American) side these directors would be known in the United States and would probably be sought out. Worldwide, these directors might not be known, so the director wouldn’t affect the gross outcome. Overall, yes, the director does affect the gross outcome domestically, but it does not worldwide.

Is there a difference among studios and the production budget?

After completing all analyses and looking over the data collected it can be said that production budget can have an effect on gross income, but there are other factors as well, including but not limited to how the director is, if the viewers like the movie, the movie genre, and the producing studio.