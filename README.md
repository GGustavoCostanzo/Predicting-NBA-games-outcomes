# Predicting NBA games outcomes

## Problem statement

The aim of our project is to build a ML model to predict the outcome of a
basketball match from the NBA regular season.
Assuming a dependence between the outcome of the match and the statistics
scored by the two competitors in the previous games, the learning phase should
give a model that will predict the winner of the match from an input that
considers the recent statistics of both teams. Defining⃗x 0 and⃗x 1 the statistics
of the home team and away team, our problem can be considered as a binary
classification with the outcome prediction y = 1 if the home team wins , y = 0
otherwise.
Since our dataset is provided with the labels (the outcome of a match) we
decided to use supervised machine learning and since we are facing a binary
classification problem we used as assessment the AUC index as in most of the
procedures.
