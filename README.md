# EuroEDA
EDA using SQL for Euro Football dataset between 2008-2016

Description
The ultimate Soccer database for data analysis and machine learning

+25,000 matches
+10,000 players
11 European Countries with their lead championship
Seasons 2008 to 2016
Players and Teams' attributes* sourced from EA Sports' FIFA video game series, including the weekly updates
Team line up with squad formation (X, Y coordinates)
Betting odds from up to 10 providers
Detailed match events (goal types, possession, corner, cross, fouls, cards etc...) for +10,000 matches
*16th Oct 2016: New table containing teams' attributes from FIFA.

Original Data Source:

You can easily find data about soccer matches but they are usually scattered across different websites. A thorough data collection and processing has been done to make your life easier. I must insist that you do not make any commercial use of the data. The data was sourced from:

http://football-data.mx-api.enetscores.com/ : scores, lineup, team formation and events

http://www.football-data.co.uk/ : betting odds. Click here to understand the column naming system for betting odds:

http://sofifa.com/ : players and teams attributes from EA Sports FIFA games. FIFA series and all FIFA assets property of EA Sports.

When you have a look at the database, you will notice foreign keys for players and matches are the same as the original data sources. I have called those foreign keys "api_id".
