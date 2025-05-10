# International-Soccer-Matches
### Section 1: 

I’m interested in this dataset because I really like soccer and I follow it a lot. Also, it gives me a lot of information about this topic in the international field.

I found this dataset on Kaggle: https://www.kaggle.com/datasets/brenda89/fifa-world-cup-2022?resource=download

The person that created this dataset is called Brenda L.

This dataset was created around 2 years ago but it covers all the international matches played from 1993 to 2022

This dataset contains information about international soccer matches during the years, giving a lot of details of every match (scores, places that the matches were played in, nations, FIFA ranks, etc.)

### Section 2:

The structure of the data is rectangular because it is a csv file and is uses rows and columns.

This data has a coarse granularity because each row represents an international soccer game.

The scope of the data is too big because it focusses on games, having scores and team that wins but not information about the players.

The soccer game data was collected from 1993 to 2022, the data has the information when has been collected.

This data has a good faithfulness, it has some missing rows but those rows doesn’t matter for the data I’m using it for. The data is very believable because it has the exact same information of each game that it can be found on internet. 

### Section 3:

First created a jupiter notebook file, then created a new dataframe from the csv file with the pandas library.

Filtered the data by deleting the columns from home_team_goalkeeper_score to away_team_mean_midfield_score because it has a lot of NaN values.

Used the pandas library to drop the columns that were not necessary.

### Section 4:

1) In this plot you can see the international matches that has been played in a neutral location, and which ones not. Most of the games are not played in a neutral space because they play in both team's countries. That's why you can notice why there is a lot of difference.

2) In this plot you can see the different result from the the international matches played, where the win, lose and draw are from the local team side. Most of the home teams ended up winning as you can see. That is what most likely happen nowdays. You can notice that the least amount of games are ties because the games are usually with a lot of goals and with a winner most of the time.

3) In this plot you can see there is the distribution of goals from the local team. The most communs are the 0, 1 or 2 goals per game, that is what happen in most of the international games. Most of the time the win by one goal. And the most commun is 1 because always the local team has an advantage, by their fans, climate, location, closest and comfier.

4) In this plot you can see the goals scored by the visit team. In this case as the last one, the most communs are 0, 1 or 2 goals. But, this time the most commun is 0 goals because for how hard it is to score on a away match. But the rest of the chart is very similar to the home goals.

You can see the plots on the Jupiter notebook(ipynb)

### Section 5:

1) In this graph you can notice the different average scores from the home team throughout the years. You can see that when a local team scores a goal or less is most likely going to lose or draw. Most of the cases if the local team doesnt score is going to lose, but if it scores at least one goal is probably a win or a draw. And when they score more than one goal in a game, they are for sure winning. Why is the draw between 0 and 1? because most of the draws in international games are 0-0 or 1-1.

2) In this graph, you can notice all the average score from the home team by continent. You can see that most of them have the same average ratio except from Ocenia and Africa that has a little difference from the other continents. In Oceania there is like 2 big countries that has the best teams in the continent(Australia and New Zeland) because of this there is a lot of goals in their favor in most of the matches. In the other hand, in Africa there is a lot of good teams in the continent being one of the hardest continent to win a game, because of their physique and their strength it is harder to score a goal in this region.

You can see these plots on the Jupiter notebook(ipynb)

