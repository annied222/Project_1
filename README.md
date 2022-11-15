# **Movies: To Spend or Not To Spend**

## **Does a movie's budget have an impact a movie's outcome, gross income or rating?**

&nbsp;&nbsp;&nbsp;&nbsp; To figure out weather or not there is a relationship between a movie's gross income and that movie's production budget there were questions that needed to be answered. These questions were developed in order to look directly at the budget vs income relationship, but also to look at other factors that may have an impact on a movie's income. To help answer the questions we created a dataset(allmoviedata.csv). This dataset was created by using a csv that had 250 of the top movies over the past 40 year. Then we found the correlating movie budget and gross income for those movies. Once we were able to that we found the directors for each movie use the OMDb API.  With the dataset we were able to answer our questions, which are as follows below along with the correlating notebook.


### **Is there a correlation between a movie's budget and the domestic/worldwide gross? **
&nbsp;&nbsp;&nbsp;&nbsp; At first glance I was of the opinion that the higher the movie budget the more money it was going to make domestically/worldwide. However the domestic r-squared value is .32, the worldwide r-squared value is slightly higher at .42 and the points on the scatter plot have a greater dispersion the higher the budget gets. I would say that a higher movie budget does not fit our assumption that the greater the budget the greater the profits.

### **Over the years how has a movie's budget changed, and has there been a correlating change in gross income, domestic and worldwide? (updates.ipynb)**
&nbsp;&nbsp;&nbsp;&nbsp;We can clearly see changes over the years in budgets both worldwide and domestic. Our datasets started from 1975 and ran all through 2018 using American made movies only. The cost of movies have had a steady incline. Possibly due to inflation and changes in technology. There are some very high outliers when it comes to budgets but for the most part has been a steady inlcine instead of drastic changes in budgets.

### **How does a production's budget breakdown in per genre, and does have an impact on the worldwide or domestic gross? Based upon that, is there a difference among studios and the production budget?**
&nbsp;&nbsp;&nbsp;&nbsp; The question for this portion was if Genre would impact the Overall Production Budget, Domestic Gross and Worldwide Gross. The data illustrates that the genre does directly impact the average production budget. The average production budget for Action movies was approximately 190,000,000 dollars per movie which was approximately 50,000,000 dollars higher then the next highest category which was Fantasy at approximately 140,000,000 dollars per movie. Additionally, the average Domestic Gross (377 mil) and Worldwide Gross (987 mil) is also the highest for Action movies. This is approximately 100,000,000 dollars domestically and 80,000,0000 dollars wordlwide higher than the next highest genre's, which were Horror and Fantasy. This also confirms that the genre does impact Domestic and Worldwide Gross.

&nbsp;&nbsp;&nbsp;&nbsp; It was interesting to note that Walt Disney pictures had one of the highest production counts but also averaged the highest production budget per movie. This would lead you to assume that if we looked primarily at the Action genre, we should expect to see Walt Disney Picture with the highest count. Data proves this to be correct as Walt Disney has the highest amount of Action movies with a total count of seven and an overall highest average production budget per movie with an average of approximately 176,000,000 dollars per movie.

### **Will a movie's production budget be reflected in the ratings of that movie?** 
&nbsp;&nbsp;&nbsp;&nbsp; When reviewing the data, we initially wanted to identify the movies with the highest IMDB ratings and the ones with the lowest IMDB ratings and then compare how the budgets for each data set identified. Within the data compiled, there was 12 movies identified as having an IMDB rating of equal or greater than 8.3 and each movie had an average budget of roughly 140 million dollars. The highest rated movie per the data compiled was The Dark Knight which had a production budget of 185 million dollars and achieved a 9.0 IMDB rating.

&nbsp;&nbsp;&nbsp;&nbsp; Conversely there was 7 movies identified as having an IMDB rating equal or less than 5.5 and each movie had an average budget of roughly 84 million dollars. The lowest rated movie per the data complied was The Twilight Saga: New Moon which had a production budget of 50 million dollars and achieved a 4.6 IMDB rating.

&nbsp;&nbsp;&nbsp;&nbsp; We then wanted to identify the movies with the highest and lowest production budgets and then compare how their IMDB ratings were. Within the data compiled, there was 12 movies identified as having a production budget of 230 million dollars or higher. Each movie had an average budget of roughly 281 million dollars and an average IMDB rating of 7.35. In terms of the lowest production budgets, there was 13 films identified as having a production budget of 12 million dollars or less. Each movie had an average budget of roughly 7.7 million dollars and an average IMDB rating of 7.08.

&nbsp;&nbsp;&nbsp;&nbsp; Based upon the information compiled we can confirm that there is a correlation with the production budget of a film and their ratings. An interesting observation was the highest budget film, Pirates of the Carribbean: On Stranger Tides had a production budget of 379 million dollars and only obtained a 6.7 IMDB rating; however, the lowest production budget film of The Full Monty obtained a 7.2 IMDB rating with a production budget of only 3.5 million dollars.

### **Does the director affect the gross outcome or does the budget?**
&nbsp;&nbsp;&nbsp;&nbsp; Based upon the analysis that was done it can be said that the number of movies that a director has done, or the director’s experience, does affect the gross domestic outcome more so than the production budget, but only to a point. That point happens to be when the average budget decreases and outweighs the director’s experience. In the worldwide gross does not appear to be affected by a director's experience, but does have the same result as the gross domestic. As the average budget decreases there is a higher likelihood of a high percent change. It is understandable for there to be a difference between the gross domestic and worldwide outcome. Majority of the movies and directors on this dataset are English speaking and/or American movies. On the domestic (American) side these directors would be known in the United States and would probably be sought out. Worldwide, these directors might not be known, so the director wouldn’t affect the gross outcome. Overall, yes, the direct does affect the gross outcome domestically, but it does not worldwide.

## **Final Analysis:**
&nbsp;&nbsp;&nbsp;&nbsp; After completing all of the analyses and looking over the data collected it can be said that production budget can have an affect on gorss income, but there are other factors as well, including but not limited to how the director is, if the viewers like the movie, the movie genre, and the producing studio.

Powerpoint: https://docs.google.com/presentation/d/19qZGrXJtz0zmFubgmXvJQRvEElXN5s8l9Z-Hk1jnCjk/edit#slide=id.p
