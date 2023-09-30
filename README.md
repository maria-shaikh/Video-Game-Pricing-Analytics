# Video-Game-Pricing-Analytics
The primary focus of this project is to investigate the impact of customer sentiment on video game pricing. 

## Executive Summary

The primary focus of this project is to investigate the impact of customer sentiment on video game
pricing. Our analysis is based on a comprehensive dataset obtained from SteamDB, a prominent video
game database, which includes information such as release dates, reviews, and prices. Leveraging
sentiment analysis, we predict the pricing premium associated with video games. This study holds
substantial significance in the competitive video game market as it aims to offer data-driven
recommendations for the optimization of pricing, discounting, and game development strategies.
Key findings of our work include the following:
In reviews left for Counter Strike Global Offensive, the most common words used were “game”, “play”,
and “get”. Meanwhile, when running an LDA model we find the majority of topics discussed regarding
the game include the gameplay itself and the “Russian” aspect and themes of the game. The most
common words used in reviews for Persona 5 Royal include “game”, “persona”, and “time”. From the
LDA model we find that much of the reviews discuss the wide variety of character offerings within the
game and the time it takes to fully complete the game. Call of Duty: Black Ops 3 saw reviews commonly
using words such as “game”, “zombies”, and “map”. Using the LDA model, we see much of the reviews
discuss the multitude of maps available to play through the online multiplayer as well as the zombies
mode.
We can conclude that overall, the random forest model has better predictive performance than linear
regression for forecasting the prices of video games based on customer reviews. We arrived at this
conclusion by analyzing the Random Forest and Linear Regression RMSE under three different sentiment
analysis methods: Afinn, Bing, and Syuzhet. By comparing RMSE of different methods, we also
concluded that Syuzhet is the most efficient method for sentiment analysis.

