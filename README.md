## Project Description 
This notebook predict the average_rating of board games depending on many features including (minplayers, maxplayers, playingtime, ...)

## packages used 
- pandas 
- matplotlib
- sklearn
- seaborn
## used data set 
[board games data set](https://github.com/ThaWeatherman/scrapers/blob/master/boardgamegeek/games.csv)

## Algorithms used
- LinearRegression &rightarrow; mean-square-error : 2.0788
- random forest model &rightarrow; mean-square-error : 1.4458
   - It is a supervised learning algorithm. Like you can already see from it’s name, it creates a forest and makes it somehow random. The „forest“ it builds, is an ensemble of Decision Trees, most of the time trained with the “bagging” method. The general idea of the bagging method is that a combination of learning models increases the overall result.
