# Udacity_pro2_investigate-TMDB-dataset

## Introduction

This is the 2nd project for my nanodegree program at Udacity. In this project, I work on TMDb movies dataset to complete my investigate and answer the research questions I designed for my project. This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue etc. 
The tools I used is juypter notebook for the data exploration, data wrangling and data visulization. The libraries included in the project are listed as follows:
>* Pandas
>* NumPy
>* Matplotlib
>* Seaborn
>* Statsmodels








## Questions designed for the investigation
* Which year has the highest release of movies?
* Which genres are most popular from year to year?
* Movie with longest and shortest runtime?
* Which movie has the highest or lowest Profit?
* What kinds of properties are associated with movies that have high revenues?







## Conclusion
Overall, we can see a increase trend regarding the number of the movies being released over the years from the investigated data. There is a positive relationship among the popularity and budget with the revenue of the movie, meaning that more popular and more money spent in creating the film will lead to more revenue of the movie. Below are the sub-conculsions I found to answer my research questions I raised before
* We can see a growing trend of the nuble of movies releasing each year and 2014 is the year has the highest release of the movies. 
* Drama genre has the highest release of movies followed by Comedy and Thriller while the Foriegn, Western and TV movies genres have the least release.
* The movie namely'The Story of Film: An Odyssey' has the longest runtime while there are four movies with the shortes runtime with only 2miutes.
* The movie `Star War` has the highest profit, which is also one of my favorite movies. The movieThe Warrior's Way has the lowest profit, of which I never heard.
* There is a statistical significant evidence that the explanatory varibles budegt and popularity has a positive relationship with our response varibale revenue(p-value=0.000) Also, 46.2% of our explantory variables could be explained by the model.










## Limitations
* In the data cleaning process, I just dropped all the null data. However, it may have the possiblities that these data could change the trends and pattern of the investigated data. 
* In the data cleaning process, I just dropped all the data whose budgest and revenue is '0'. However, it may have the possiblities that these mistakenly input data could change the trends and pattern of the investigated data. 
* By doing the multiple linear regression, I assumed all the aussmptions of regressions are met. However, we may need more furether information to show if these assumptions are met.
