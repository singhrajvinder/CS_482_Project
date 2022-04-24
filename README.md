# [CS482 Project Proposal](https://www.kaggle.com/competitions/mens-march-mania-2022/overview/description)
Submitted by: Muhab Elgamal, Christian Saliski, Rajvinder Singh

1. What is the problem that you will be investigating? Why is it interesting?

  -  Our group has chosen to work on March Machine Learning 2022. This is a Kaggle competition in which we focus on predicting likely winners for each possible matchup at each round of the tournament. This has piqued our interest because billions of people participate in making their own brackets for likely winners each and make bets on who would win the basketball tournament. Solving this problem will greatly help us choose a more suitable bracket instead of making guesses and using our intuition.

2. What reading will you examine to provide context and background?
  
  -  With dealing with sports, there is a ton of data you can find online about players, and team stats. With betting, you can clearly find an underdog of a game. But in order to predict 2022 game probabilities we need to look at season games and previous year data. For example, If a team is found to be the number 1 seed and has a 95% chance to make it to round 2, it is clear that they will most likely make it to round 2 which increases the probability of a certain game happening.
 
3. What data will you use? If you are collecting new data, how will you do it?

  -  Data provided by Kaggle and taking the average of wins per team spreads. Comparing values given in the data set to each team.Regular season and tournament  data from past years for teams are given and can be used for new data. All data for each team has been given to us with each team's scores and wins.

4. What method or algorithm are you proposing? If there are existing implementations, will you use them and how? How do you plan to improve or modify such implementations? You don’t have to have an exact answer at this point, but you should have a general sense of how you will approach the problem you are working on.

  -  There are implementations of this from previous years, however this year has more data compared to the previous years. We will use the previous year's code as a reference. We will have to train a model on previous years and performance during the season. Then with that model, predict a winner at each point in the bracket. So this would look similar to the random forest that we created during the midterm. I have noticed that most implementations use numpy. We will replace numpy with Jax numpy to speed up calculations. 

5. How will you evaluate your results? Qualitatively, what kind of results do you expect (e.g. plots or figures)? Quantitatively, what kind of analysis will you use to evaluate and/or compare your results (e.g. what performance metrics or statistical tests)?

  -  We expect to have probabilities for each seed and compare the two teams by their predicted probability and pick a winner for that game. The results will be compared to winners in real life and see if we predicted the correct winner.

#setup/ Documentation 
