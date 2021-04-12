Question of Interest:
	In the sports world, predicting games correctly can be very valuable. There are many ways to predict a winner, such as the current record, players, and who the home team is. Our goal is to combine these factors to get a single score that will predict who the winner of the matchup is. Our hope is to be able to predict NBA games with around 75% accuracy, but that may be a bit ambitious.

Data Set Description:
	For our project, we will be making use of five separate datasets. The first dataset, games.csv, is a table containing team data for every game in the NBA from 2020 to 2004. It contains the teams points scored, field goal percentage, and free throw percentage (for the home team only). The next dataset, games_details.csv, contains the player data for every game. Specifically, their minutes played and field goals made. Players.csv contains just player names, team, and season played. Ranking.csv contains the team's record on every date of the season. It shows wins, losses, and win percentages. Lastly, the teams.csv contains the team data. It shows the teams founding year, city, and stadium capacity.
 
games.csv : all games from the 2004 season to last update with the date, teams and some details like number of points, etc.
games_details.csv : details of games dataset, all statistics of players for a given game
players.csv : players details (name)
ranking.csv : ranking of NBA given a day (split into west and east on CONFERENCE column
teams.csv : all teams of NBA
Link: https://www.kaggle.com/nathanlauga/nba-games?select=games.csv
Methods:
	We plan on using a GMM to predict if a team wins or loses when playing against any specific team. We will use points scored by the team, points scored against, home/away record, current ranking, win percentage, and win percentage against the team they are playing against. Once this project gets underway we will reassess and potentially add some more components such as whether or not the normal starting five are playing. We could also add arena size. We will have to do some prep work generating some of these components from the current data but most are already given. We also hope to see if there are certain statistics that carry more weight than others.
