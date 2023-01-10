# MODELLING KINGS LEAGUE SCORES

Modelling football scores is the process of constructing a mathematical model which can be used to predict the results of football matches based on data from past games. It involves taking historical data about teams’ goals scored and conceded and using it to build a predictive model for future matches. This model can then be used to estimate the likelihood of a particular result, such as how likely a particular team is to win a certain game. Modelling football scores can be used for a number of different applications, such as predicting the outcome of an upcoming game or providing insights into team performance over an entire season.

## Introduction

Football data and analysis is a field of study that deals with the use of data, statistics, and analytics to gain insights into the game, the teams, and the players. This field can be used to improve the performance of a team, to identify recruitment targets, to identify tactical strategies, and to better understand the game. Football data and analysis also provide valuable insights into the game and its players, which can be used to inform decisions on team selection, player development, and team tactics. Football data and analysis can also help to understand the financial dynamics of the sport, including revenue, expenditure, and investment.

In this project I wanted to build a model to predict the results of the matches of the **Kings League** teams. Being a newly created league, there is very little data, which also poses a challenge when building a predictive model.

## What is the Kings League?

The **Kings League** is a 12-team competition that features presidents from each team drawn from the world of football, streaming, and social media. The format of the league is seven-a-side, which means that each team is composed of only seven players on the field at a time, instead of the traditional 11 players.
Each team has a squad of 12 players in total, with the first 10 players being picked via a draft. This draft was streamed on the popular streaming platform Twitch in December, and players who were selected were chosen from a pool of those who had signed up in November. Anyone could register to be a part of the draft, regardless of their background or experience level.

The remaining two players on each team are considered "ringers." These players are usually former professional football players, but in some cases, they may be current professionals as well. The 11th player on the team must be the same for the entire season, whereas the 12th player can change from week to week. This allows teams to adjust their strategy and lineups depending on their opponents and the specific challenges of each game. The league also could have some specific rule set, or scoring system to make it more interesting or competitive.

## Methodology

Football methodology analysis is a systematic approach to understanding how football teams or players function in a game. It involves looking at the factors that contribute to their performance and how those factors relate to their performance in the long-term.

  * [Predicting the FIFA World Cup 2022](https://towardsdatascience.com/predicting-the-fifa-world-cup-2022-with-a-simple-model-using-python-6b34bdd4f2a5)  
  * [Predicción en fútbol a partir de los goles marcados: La distribución de Poisson](https://vencex.com/2018/01/01/prediccion-en-futbol-a-partir-de-los-goles-marcados-la-distribucion-de-poisson-i/)
  * [Predicting Football Results With Statistical Modelling: Dixon-Coles and Time-Weighting](https://dashee87.github.io/football/python/predicting-football-results-with-statistical-modelling-dixon-coles-and-time-weighting/)
  
This study is based on the book, _Fútbol, Análisis y Síntesis_. This book is an in-depth look at the game of football and the techniques and strategies that make it so exciting. This book uses detailed diagrams and examples to help readers understand the concepts he is describing. He also includes a comprehensive glossary of football terms.

![](./images/futbol_analisis_y_sintesis_cover.png)

I have applied a simplification of Dixon-Coles algorithm. Dixon-Coles is a algorithm used to model football scores. It is an extension of the Poisson Model, which is a statistical approach to predicting the probability of a given number of goals being scored in a match. The Dixon-Coles model further refines the prediction by incorporating additional parameters into the model such as home advantage, the form of each team, prior matches between the teams, travel time and weather. The final prediction is made by weighting each parameter according to its importance. This makes it more accurate than the Poisson model and it is now widely used by sports data analysts.

Another algorithm that I have studied is the Maher algorithm. Maher algorithm is a predictive model designed to predict the outcome of football matches. It takes into account various factors including the teams’ recent form, home or away advantage, current standings in the league, past head-to-head record, and key player availability. The algorithm uses a Bayesian probability model to calculate the probabilities of the outcomes of each match. The model is based on over a decade of research and utilizes over 400,000 matches from top-tier football leagues around the world. It is a popular tool for creating predictive models for sports and is widely used by bookmakers and sports analysts alike.

## Data Collection in Football

Data collection in football has dramatically increased in recent years with the introduction of advanced player tracking systems. These systems collect and analyse data from every aspect of the game providing an unprecedented level of insight into performances. This data is used by teams to gain a better understanding of their players, opponents and the game in general. It can be used to identify strengths, weaknesses and develop strategies. Player tracking systems also enable coaches and scouts to analyse the physical and tactical performance of players in real-time, allowing them to make informed decisions in team selection. Data is also used to inform players of their individual performance, improve tactical decision making and inform coaching. Ultimately, effective data collection and analysis can lead to improved team performance, success and greater fan engagement.

### Sources

Football data sources are important because they provide valuable information and insights on team performance, players, game results, fixtures, and standings. This data can be used to gain a better understanding of the sport, gain insights into player and team performance, develop predictive models for predicting future game outcomes, and use to engage in strategic decision-making. Football data sources can also be used to aid in the creation of more accurate and sophisticated analytics that can help organizations make better decisions about their strategies and tactics.

  * [Kings League infojobs](https://kingsleague.pro/)  
  
GitHub has several repositories that contain a wealth of publicly-available football data and models. For example, some repositories include a variety of football data, including team and player statistics, as well as several models based on that data. Additionally, GitHub hosts several repositories of football prediction models, as well as a repositories of football analytics and simulation code. Finally, the [538 Sports Database](https://data.fivethirtyeight.com/) repository contains an extensive collection of sports and football data, including a variety of stats, player ratings, and more.  
  
  * [soccer-spi](https://github.com/fivethirtyeight/data/tree/master/soccer-spi)  
  * [football-prediction-model](https://github.com/pawelp0499/football-prediction-model)  

### Guide to Kings League data and APIs

You can write code and code and then web scraping or you can use the following API:

  * [API y website de la Kings League Infojobs por temas didácticos](https://github.com/midudev/kings-league-project)
 
You can also find code to apply web scraping and find information and data about classification and schedule in this repository
