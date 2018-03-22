---
layout: post
title:      "FantasyFootballOnRails"
date:       2018-03-22 19:06:23 +0000
permalink:  fantasyfootballonrails
---


For my Rails application I decided to build the project based on something that I love, and a rails project about my doggos would be super boring so I went with Fantasy Football!

I have shown the project to a lot of my friends and it has been a huge hit. Basically, you create a team in a league, you can have many leagues and each team in that league has 5 players (a qb, rb, wr, te, and dst). Right now the playing style is kind of dull, the scores are based on ADP (average draft position) based on a website that I scraped for the project. (many thanks to fantasypros.com). During the Football season however is when this game will really become fun. 

So you can have a few teams within a league, but a league can only have 10 teams until it becomes full. So get 10 of your buddies, make a few teams in a league, and see who scores the most points! During the season, players will have game times, fantasy points per game, and rankings within their position. The team of 5 players with the highest fantasy points for that week will win! Fantasy points will also be accumulated for the league throughout the year, so the top leagues will be featured and the top team in each league will be featured as well. 

Now to the technical aspects of the application!

There are several different models I used to make this application. We have a User, Player, Position, Team, League, and Mascot models. There are join models as well for League_players, team_players, and Team is a join table for League and Users. Position and Mascots are just simple addons to Players and Teams respectively. Every form has validations, not only instant validations within the HTML (using required), but also using validators in the Model. An example is that a User must have an email and password, Players must have positions, etc, etc. 

2 Scopes of methods were used. I used a Team.best_team class method in order to find the best team of all the leagues and show them off on the welcome screen. I also have several instance methods, used for finding the score of a team, creating a custom validation, and also interpreting mascot_attributes within a nested form. 

My application takes advantage of RESTful resources, even as far as creating teams within leagues using "/leagues/:league_id/teams/new". 

I have been having a TON of fun with this application. I am stoaked to be able to use it this fall to play a new version of fantasy football with my friends. 
