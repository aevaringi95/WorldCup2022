# World Cup 2022 - Prediction


<div id="header" align="center">
  <img src="https://media.giphy.com/media/kgsqn9gCVAQ3YM3C2f/giphy.gif" width="100"/>
</div>


# Objective

The aim is to create a prediction model that accurately predicts the winner of the FIFA World Cup 2022. It simulates each game based on a score for each team. 


# Resources

Idea similar to:

https://fivethirtyeight.com/methodology/how-our-club-soccer-predictions-work/




# Features

- Attacking performance

- Defensive performance

- Recent performance

- Opponent performance

- Advantage? (Home advantage etc.)


# Approaches

There seem to be two main approaches used for football outcome predictions:

## Indirect

The probabilites for a home win, draw, and away win are calculated indirectly by first estimating the number of goals scored and conceded by each team. The proabilities are then calculated based on simulations.

## Direct

The probabilites are calculated directly, that is without explicitly estimating the number of goals scored and conceded. For example by using logit or probit regression. 

