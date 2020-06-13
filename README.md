# Stats170B Final Project
Attached are the different scripts for carrying out the final project. 
To run the Notebook.ipynb, there are three associated csv's that need to be utilized: 'qb_by_year.csv' and 'season_qb.csv' are used for initial visualizations while 'qb_sample_data.csv' is the sample data that is used when running the ARIMA model that is conducted in Notebook.ipynb. 

If desired, feel free to visit some of the other Python notebooks that are described below: 

  MainPlayerStats.ipynb is a script that scrapes pro-football-reference.com for the statistics of interest in our project. 
  
  PCA.ipynb is a script that utilizes Principal Component Analysis to examine the relationship of players' performances with their teams' offensive statistics in the past season and their opponent's defensive statistics in the past season. 
  
 The Random Forest Regression and Ridge Regression notebook contains the hyperparameter tuning of the random forest models for each football player position, and the ridge regression model with PCA. It loads a csv of the merged football data, excluding tweet data as we determined it was not significant to the model. Table comparing RMSE of models and plots of predicted vs actual fantasy scores are created. 
 
The GetTweets notebook contains a script to scrape tweets about football players during the football seasons. We are mainly interested in the tweet text, and not so much the other variables. 
TweetsSentimentSample is a notebook containing tweet text cleaning and sentiment analysis with VADER. The result is a new dataframe tweet sentiment scores appended to the original table. Because of the large amount of tweet data, this workbook only uses a small sample. 

The MergeNFL notebook contains a short script merging the different football game data into one dataset. This dataset is later merged with the tweet dataset in the MergeTwitterNFL notebook.
