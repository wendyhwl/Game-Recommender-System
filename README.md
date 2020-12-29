# Game-Recommender-System
Simple game recommender system using [Steam Store Games dataset](https://www.kaggle.com/nikdavis/steam-store-games). Given a game name, the system returns 20 most similar games based on selected features.

## Dataset
The steam.csv file contains 27075 rows and 19 columns. Each row represents a game offered on the Steam platform and the columns contain information of the corresponing game, such as name, developer, genre and ratings. The data is gathered in May 2019, which contains almost all the games on Steam prior to that date. 

## Method
This game recommender is purely content-based. We combine the chosen features and compare them using [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity). The chosen features are: developer, categories, genres and steamspy_tags. 

[Click here](https://github.com/wendyhwl/Game-Recommender-System/blob/main/game_recommend.ipynb) for detailed implementation steps, conclusion and findings.

## Ackowledgement
- Reference from Rounak Banik's [Movie Recommender Systems](https://www.kaggle.com/rounakbanik/movie-recommender-systems)
