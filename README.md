# Dota2_NetWorthPredictor
Liear regression model to predict the net worth of a single player after the game is played


### Aim of the research
  The main goal of this research is to study and analyze the data from a strategy game, called DoTA 2, where there are exactly 5 players on both teams that are thriving to destroy the enemy's base, and usually, the one that has more resources wins. In this research, we will study the relationship between various statistical parameters that could be gathered during the game, and will analyze how they influence the amount of resources each player is able to gather in the end. Our aim is to figure out which parameters are more significant than others, and based on this knowledge, make a model that accurately predicts an amount of money, each player finishes a game with. Of course, this does not make much sense for those who do not play the game but still it can be interesting not only for players and bookmakers, but also usual people, who are curious to discover new fields.

### Data used
  We used dataset, that could be downloaded from https://www.kaggle.com/devinanzelmo/dota-2-matches


### Results
As a result we figured out that there is a linear relationship between the majority of parameters, and in hypothesis testing using Pearson correlation test, we have found parameters that proved to be most significant in our future prediction. Finally, after making sure that linear regression model is applicable to our task, we have trained a multiple linear regression model. It gave us a successful prediction of a friend on real-world data, that it has not seen before.