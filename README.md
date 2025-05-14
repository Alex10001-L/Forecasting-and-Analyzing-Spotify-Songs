# Forecasting-and-Analyzing-Spotify-Songs
                                                  Summary
This project explores the impact of song genre on its popularity and aims to forecast genre trends over the next 12 years. By analyzing four Spotify datasets—Hip-Hop, Pop, Rock & Metal, and Other Genres (e.g., Folk, Country, R&B)—we will examine the relationship between genre and popularity from 1999 to 2019 and predict future trends. The study will also investigate factors such as danceability, energy, and loudness, which may influence a genre's popularity. 

Recognizing that music trends often follow audience preferences, we will account for factors like seasonality and generational shifts in music taste. In consderation of of possible seasonality and trend, we can use models such as Holt-Winters or SARIMA to capture such patterns in the dataset which is then used for our predicitons. However if seasonality isn't as prominent that we may want to consider alternative models such as ARIMA, Holt, or even Simple Exponential Smoothing. The study's results will provide valuable insights into how listener preferences, artist success, and emerging trends shape the popularity of music genres. These findings will be useful for industry stakeholders, including artists and producers, to navigate and capitalize on trends in the evolving music landscape.

                                                  Dataset
The following is the raw dataset that we'll be using for our predictions. First it'll be cleaned and processed via python, then analysis will be made using R.
1. https://raw.githubusercontent.com/TreeBeeTea/dso_project/refs/heads/main/Spotify%20Most%20Streamed%20Songs.csv 
2. https://raw.githubusercontent.com/TreeBeeTea/dso_project/refs/heads/main/songs_normalize%20(2).csv 

                                                  Research Question
1. Where will these genres’ popularity be in the next few years?
2. Are there any correlation between song attributes to genre popularity? If so, which attributes? Danceability? Energy? Loudness?

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ 

Coding Language: R and Python
