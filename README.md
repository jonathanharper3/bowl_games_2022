# bowl_games_2022

This is my attempt at a tool that will predict the outcome of the 2022/23 college bowl season games. I used Massey Ratings data to train three different
random forest classification models and compared these predictions to the predictions my friends and I made at the beginning of the bowl season.

This code includes regular expressions, that were used to scrape team names, scores, dates, and locations from a .txt file that was obtained from
Massey's website. This .txt file includes the matchups and outcomes of each game played during a given year. It also includes the creation of a dataframe
that matches data from these matchups with expert analyses to further inform the model.

The 2022/23 iteration of this model performed subpar, only correctly predicting 60% of the bowl games played. Further steps we can take to improve this
prediction can be found on the last slide of the included ppt presentation.

Written by Jonathan Harper
