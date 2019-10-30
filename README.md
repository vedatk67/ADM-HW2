# ADM-HW2 Homework 2 - Soccer analytics

Group 18

- Gabriele Giannotta
- Michele Meo
- Vedat Katirci

The purpose of this assignment was to perform an analysis on the largest open collection of soccer-logs collected by [Wyscout] (https://wyscout.com/) containing all the spatio-temporal events (passes, shots, fouls, etc.) that occur during all matches of the entire season 2017-2018. Our analysis is performed only over the Premier League dataset.


The repository consists of the following files:

  1) main.ipynb :
    A Jupyter notebook which provides the solutions to all research questions.
    
   ### Exploratory Data Analysis
    
  [RQ1] Who wants to be a Champion? During a season could happen that a team has bad periods. For example, more than three consecutive games lost, or it could have a positive trend where it seems to be unbeatable. Let's visualize this trends!


  [RQ2] Is there a home-field advantage? It is generally believed that there is an underlying home field advantage in sport, i.e. an highest probability of winning of the home team. Let's check for this.

  [RQ3] Which teams have the youngest coaches? Rank all the teams by the age of their coach and show the 10 teams with the youngest coaches.

  [RQ4] Find the top 10 players with the highest ratio between completed passes and attempted passes. For this task, consider all the different types of passes, and as specified in the website, a completed pass has tag 1801 (accurate event).

  [RQ5] Does being a tall player mean winning more air duels? Soccer is a physical game, and it happens often in a match that players are involved in air duels (i.e. when two players are contending for the ball while it is not on the ground). Make a plot that shows the dependency between height of the player and the ratio of air duels won with air duels attempted.

  [RQ6] Free your mind! Go further with the EDA (Exploratory Data Analysis) showing a new interesting result about the dataset that you found. We did an analysis about the correlation between the mean age of the team and the final score reached by them at the end of the season.

  ### Core Research Questions
  
  [CRQ1] What are the time slots of the match with more goals? 
  Make a barplot with the absolute frequency of goals in all the time slots.

  [CRQ2] Visualize movements and passes on the pitch! Here we try to focus our attention on the zones that a player covers during a match. For each event, we have a pair of coordinates, that are respectively the starting and ending point of that event.



2) codesforquestions:
  In this folder there are all the individual codes.
  
3) theory.ipynb:
  Ansewers for the theorical questions.

  
