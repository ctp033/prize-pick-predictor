# prize-pick-predictor
Model used to predict if players will hit the over or under on prize picks

## STEPS

### Phase 1 Extraction + Storage (CURRENT STAGE)
Get and store important data locally or on cloud 

MLB API GITHUB:
https://github.com/toddrob99/MLB-StatsAPI

Data Structure
Database

Players Table (player id and name)
Model
player id, date, opponent, stat (home run, hit), prop line, actual statistic, outcome (over or under), 
recent preformace (average over last 10 games), opponent stats, injury status, park factor?, weather 

### Phase 2 Transformation
Using PySpark or SQL get and transform needed data

### Phase 3 Model
Make a model

### Phase 4 Prediction API
Flask API? not sure for what

### Phase 5 Dashboard?

## Current Road Map
1. Get Line of data for a single player (hits, date of game, opponent, home team, etc.)
2. Get line info from odds api for current information to see format
3. Get lots of data from both



