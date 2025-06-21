# prize-pick-predictor
Model used to predict if players will hit the over or under on prize picks. Currently, you must run the code manually with the pitcher handedness, and line from prize picks. 


## STEPS

### Phase 1 Extraction 
For data extraction, I used pybaseball's statcast_batter function. This turned out to work amazing, as it provides extremely detailed at bat data for batters for free. A huge thnak you to the devs for making it open source. In addition, it is very recent, being able to pull data from games from the day before. After getting a dataframe consisting of data for a game, I create features that help improve the model (recent at bat data). 

### Phase 2 Transformation
I transform the data to get important columns that help gather sliding window aggregates to better improve the mode. 

### Phase 3 Model
I selected a negative binomial model that is used to train and make predictions on a players hits. 

### Next Steps
For the model, I learned it is very hard to predict a players preformance. On a player level, it is extremely unpredictable, and hard to judge. That being said, there are many additional features that could be made that could look to improve upon my current model. Some features are as follows:
Pitcher ERA
Stadium Factor
Weather/Wind
If player is home?





