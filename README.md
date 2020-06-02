# Dota-2-ML
Here I use machine learning methods in Python to predict Dota 2 match outcomes

Aside from sports, I am also a video game lover. This is a machine learning project that I completed where I use logistic regression 
coupled with grid search cross validation from the Sci-kit Learn library in Python. The goal is to use hero selection from both teams
to predict which team will win the matchup. In other words, before the game begins, each individual player will get their choice to 
select a hero from the roster of characters. In the data, each character is represented as a dummy variable. The characters are not
all the same, meaning each one has different attributes, leading to the case where some characters perform better against some of the
cast, but worse against other characters. These matchups of characters sometimes exhibit patterns, and I want my model to be able to
predict which team will win the match, based solely off of the character selection.

Data is from the UCI Machine Learning Repository:
https://archive.ics.uci.edu/ml/datasets/Dota2+Games+Results
