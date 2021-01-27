# NBA-Guard-Predictor
Utilizing Decision Trees &amp; Random Forests in developing a model which predicts if the NBA player is a guard based off his in-game statistics.

## Objective

- Basketball is becoming more positionless every year, where we have players playing both Point Guard and Power Forward
- Objective of project -> determining if a player is a Guard since this position in particular is becoming more obsolete
- Developing a model using both a DC and RF to predict if an NBA player position is a guard - classification problem
- Using precision, recall, and F1 score to assess the accuracy in determining guard position
- Targetted data -> Guard: 1 if guard, 0 if other position 
- Features -> Per Game (Minutes, Points, Rebounds, Assists, Steals, Blocks), Defensive Rating, Offensive Rating, Freethrows (%, Attempts), % (True Shooting, Field Goal, Assists), 3 & 2 Point (attempts, %) 
- Dataset extracted from [NBAstuffer](https://www.nbastuffer.com/2019-2020-nba-player-stats/) 

## Future Improvements

- Hyperparameter Optimization tool 
- Implimenting more features such as height which was not readily available on dataset but could be scraped with BeautifulSoup on other websites 
- Feature Engineering -> Combining two categories such as Assists per Game and Rebounds per Game ratio 
- Exploratory Analysis to assess each feature against another 
- Trying out Gradient Boosting and XGBoost -> Need to increase data size (could use historical data from 2016 onwards) 

## Tools used

- Numpy, Pandas, Scikit-learn 
- Jupyter Notebook 
- Microsoft Excel (.csv) 
