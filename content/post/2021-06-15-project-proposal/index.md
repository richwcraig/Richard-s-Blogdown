---
title: Current Project Proposal
author: Richard Craig
date: '2021-06-15'
slug: project-proposal
categories:
  - Proposal
tags:
  - Analytics
  - Baseball
---

# Overview
  While data analytics and baseball have become synonymous, there are still levels of the sport that remain mostly untouched by data science. Specifically, the high school level is an area where most coaches have little to no experience working with data beyond the normal baseball stats. To begin to explore data analytics in high school baseball, I will examine how data can be used to automate a routine decision that coaches have to make, setting the batting order. By introducing data to this decision, teams can make choose accurate and efficient batting orders to help them win.  

# Context
  Data analytics in baseball has exploded in the last 20 years. While most people tend to focus on the Major League level and the prevalence of data analytics within it, other levels of the sport could be improved with data analytics. Certain decisions have the potential to either be easier to make or all together automated. One of these is the simple selection of the batting order. While not the most consequential in the entirety of a baseball season, it poses an interesting opportunity to introduce a degree of automation. At the high school level, where coaches range from incredibly experienced, to relatively new, the ability to automate the decision of batting order could prove valuable.
  
  The problem for baseball coaches is that having all the data in the world is useless without the ability to analyze it and present actionable findings. If coaches had the ability to get actionable suggestions about game decisions, this could be incredibly valuable. Being able to build an efficient and effective batting order is a hallmark of an experienced coach. If there was a way to automate this decision to some degree, it could increase the likelihood that a team will win. 

# Proposal
  The specific question I am trying to answer is, can we automate the process of setting a batting order? This question will attempt to be answered using a high school varsity baseball team’s data from the 2021 season. By analyzing players’ batting performance and combining that with the factors that are valuable for each batting order position, I hope to determine what a player’s best batting slot is when compared to the other eight players in the lineup. 
  
  The outcome variable for each player will be their best batting order position based on their characteristics as well as the other starting players best lineup positions. The features that will be included to model and determine the players batting slot will be the previous season’s, batting statistics. This will include metrics such an on-base percentage, slugging, runs batted in, batting average, batting position and pitches per plate appearance. The model will also utilize the diverse scholarship and research that has already been done on this topic.
  
  It will be incredibly interesting to see how these predictions compare to the decisions made by the coaches in the previous season. I would hope to find some decisions that differ. However, as the coaches of this team are well respected, if I, as someone who has never played a game of baseball in my life, could get results that are similar to their decisions I would be thrilled. I hope to also be able to look at the games where my model would choose the same lineup and those where it differs and analyzing the team’s outcome variables just as total RBIs and their win loss record.

# Conclusion
  When it comes to baseball, data has proliferated the sport like none other, however, for coaches at lower levels of the sport, the application of this data can be daunting. If we can help coaches utilize the data that they already have to atomate certain decisions, it would allow them to apply their vast array of knowledge to more complex decisions. One decision that provides an opportunity to automate is setting a batting order. By utilizing a high school varsity baseball team’s previous season data, I hope to be able to be able to determine the optimal batting order given nine players.
  
  While it is possible that this project can applied to teams at a variety of levels, further study would be necessary. However, if the model can begin to learn on this dataset, larger datasets from multiple teams could potentially increase the model’s effectiveness for a variety of levels. Automating this kind of decision could be also incredibly useful in other areas of the sport. These same kind of principles of taking when a player is effective compared to other players can be applied to decisions about who should be the starting pitcher and when and who should relive them.
  
  The largest limitation of this project is the relatively small dataset that I am working with. In the 2021 season, the high school team only played 16 games. On top of that, due to Covid-19, for close to two weeks, half of the varsity squad was quarantined. This will reduce the number of at bats for those players. Thus, a major area of further research would be looking at this same team in the next season and evaluating the players that are still playing to determine the model’s effectiveness. This study could as well be used to determine any potential updates to the model. Beyond just this team, as was mentioned in the previous paragraph, the ability to work with data from a variety of teams at several levels, could allow the model to be applied to teams other than just the one being studied. 
