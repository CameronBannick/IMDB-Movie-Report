# IMDB Movie Analysis
## Goal
The goal of this project was to gather enough data from a variety of different sources to compile in a database. From there, we set out to answer three very specific hypothesis which will be discussed later.
## Project
I began the project with three CSV files (Title_Basics, Title_Genres, Title_Ratings) and used those as a basis for a mySQL Database. Then I expanded on this information using the TMDB API and making several API calls to include more financial information about the movies I was given. Then, after I felt enough data was extraced, we used every to do three hypothesis test to gain insight on movie revenue in the post-pandemic Worldl
## Hypothesis
### Does the MPAA rating of a movie (G/PG/PG-13/R) affect how much revenue the movie generates?
After clearing the assumptions of data normalcy and testing for equal variance, an ANOVA test was used to conduct our hypotheis test. I found there is a significant difference in certain movie ratings and revenue. The exceptions are as follows
     - G and NC-17
     - G and R
     - NC-17 and NR
     - NC-17 and R
     - PG and R
### Do movies that are over 2.5 hours long earn more revenue than movies that are 1.5 hours long (or less)?
After clearing the assumptions of outliers, normalcy, and equal variance I used a T-Test to test this hypothesis. I found that there is a significant difference in revenue between movies that are 2.5 hours long or more and 1.5 hours long or less. Since this was a two sample test, more work needs to be done to figure out by how much and to adjust for inflation.
### Did movies in 2017 make less money than movies in 2011
After clearing the assumptions of outliers, normalcy, and equal variance I used a T-Test to test this hypothesis as well. The test did show a significant difference in revenue between those two years. However, like before, since this was a two sample test, more work needs to be done on the difference and also to adjust for inflation.
## Conclusion
So we can say from sure now that there are three things that can effect a movies revenue; the length of the movie, the rating of the movie, and when the movie was released. So the questions asked are whose seeing it (rating), for how long (length), and when (release year). 
