# Opponent's Chance Origin Analysis
This project is a main focus of the UCSD Men's Soccer Analytics Team and has real impact on game-time decisions made by coaches.

## Introduction
This project aims to analyze how opponent's create their goal scoring chances.

Collected the data manually using a custom built stat tracking software. Tracked every action related to a goal scoring chance by watching film. Wrote algorithms to transform data and analyze for visualization. Wrote reports for coaches to adjust training/game plans.

## Details
We can start by looking at the spatial distribution of where opponent's get shots. These chances are most likely to produce goals. 

![Shot distribution Map](assets\shotsMap.png)

As we can see most shots are around the middle and top of the box. 

Another big aspect of goal scoring chances is the pass before the shot (Shot assist). These are a big indicator of how opponent's are setting up their chances to shoot.

![Shot assist Map](assets\shotAssists.png)

Here we can see a lot of these shot assists are passes coming from wide into and around the middle/top of the box.

Now we want to look into how these opponent's are creating these goal scoring chances.
 - Where their chances are originating
 - How their chances are originating
 - What players are involved in the chance origin

Due to the sensitive nature of this information I have displayed a graph below the contains **randomly generated data** of this nature but demonstrates the visual that would correspond.

![A randomly generated plot of chance origins](assets\randomOpponentOriginsMap.png)

The information that you can get out of these plots on the actual data include where a team is struggling and where they should focus on cleaning up mistakes. You can also see which players are giving up the most chances and how/where.

We can use this information to come to conclusiions and formulate improvement plans

![Alt Text](assets\histChanceConcededX.png)
![Alt Text](assets\fieldChanceConcededMajority.png)

As seen we can come to the conclusion that their are too many turnovers in the defensive third and we can focus on improving that area.

## Applications
This project is applicable to both post game reports (How did the opponent get chances against UCSD) and scouting reports (How did the opponent get chances against other teams)
What you saw above is an example of general post game analysis. You can also analyze opponent's chances against other teams and note down information that is useful ahead of game time.
 - Which players on their team start their teams chances (Biggest tacklers etc.)
 - Which players are most involved in the buildup to their chances
 - Which players are the ones that finish the chances (Shooters). These are the players they are looking to get the ball to.
 - Identify goal creation style (Set pieces, Buildup play, Counterattacks, etc.) to focus training and preparation ahead of time.

Therefore this project is able to have a big impact on the decisions made ahead of game time and provide real benefit.





