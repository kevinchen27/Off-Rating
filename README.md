# More threes, more offense?

The three-point revolution. Moreyball. Whatever you may call the high rate of threes being attempted in today's NBA, it is a playstyle that seems like it is here to stay and seemingly for good reason. A team such as the Houston Rockets will probably point to their offensive and overall success in recent years as evidence of the benefits of shooting more threes. Players are told to minimize midrange shots (shots between the paint and the three-point line) and teams like the Rockets almost avoid them completely. But, are these Houston Rockets teams outliers because of their arsenal of shooters, or does shooting more threes actually improve a team's offense?
<br>
<br>
To answer this question, I investigated NBA team data from 2007 (when Daryl Morey took over as General Manager of the Rockets) until the most recent NBA season. The metric I decided to include in my assessement was Offensive Rating, since it is widely used as the overall measure of a team's offense. Offensive Rating is the number of points scored by a team per 100 posessions and standardizes the points scored by teams. Thus, my initial hypothesis was that if shooting threes is beneficial for the team, then their should be a correlation between three-pointers attempted and offensive rating. Likewise, if midrange shots are detrimental to a team's offense, then shooting more of them should hurt their overall offense. 

Indeed, graphs that measured these two types of shots against offensive rating showed a distinct negative relationship between a offensive rating and midrange shots attempted while indicating a positive correlation between three-point attempts and offensive performance. 

<img src="https://github.com/kevinchen27/Off-Rating/blob/master/images/OffRtg%20vs%20Midrange%20Att.png" width="400"/> <img src="https://github.com/kevinchen27/Off-Rating/blob/master/images/offrtg%20vs%203p%20att.png" width="400"/>

To investigate further, I wanted to see whether the league average offensive rating improved year-on-year along with the increase in threes attempted. Interestingly, there were quite a few years where the NBA's average offensive rating was higher than in years where the league as a whole attempted more threes. Yet, over the past three years when three-point attempts have ballooned, the league's average offensive rating has skyROCKETed (get it?).

<p align = "center">
<img src="https://github.com/kevinchen27/Off-Rating/blob/master/images/Offleader%203p.png" width="500" align = "middle"/>
</p>

As an even stronger argument for attempting more threes, every year's top offensive team almost always attempted more threes over the course of the season than the league average. The only exception to this was the 2008 Utah Jazz, who attempted almost 6% fewer threes than the league and yet led the NBA in offensive rating. But, if the best offensive team is the standard to adhere to, shooting more threes will *probably* give you a higher chance of leading the league in offense. 

<p align = "center">
<img src="https://github.com/kevinchen27/Off-Rating/blob/master/images/off%20rtg%20leaders%20vs%20league.png" width="500" align = "middle"/>
  
 Surprisingly, the best offenses in the league didn't always attempt fewer midrange shots than the league average. As a matter of fact, in the most recent season of the three-point revolution, the Golden State Warriors led the league in offense while attempting a considerable amount of midrange shots. This could be attributed to the shot selection and efficiency of Kevin Durant, who shoots at a high volume from midrange but with astounding accuracy, making over 50% of his shots from that range.
  
<p align = "center">
<img src="https://github.com/kevinchen27/Off-Rating/blob/master/images/offrtg%20mid%20leader.png" width="500" align = "middle"/>
</p>

Even if we expand on our selection of the NBA's best offenses to include the top 10 teams in terms of offensive rating, many of these teams also placed among the top 10 in three pointers attempted. On the other hand, teams that were in the top 10 in mirdange shots attempted didn't quite crack the League's top 10 offense as frequently. In fact, teams in the top 10 for midrange shots attempted never comprised even half of the the league's top 10 offensive teams.

<img src="https://github.com/kevinchen27/Off-Rating/blob/master/images/3pt%20vs%20top%20off.png" width="400"/> <img src="https://github.com/kevinchen27/Off-Rating/blob/master/images/midrange%20top10.png" width="400"/>

The data suggests that attempting more three pointers will likely help you generate better offense too. That is not to say midrange shots won't propel you to the best offense in the League (cue 2008 Utah Jazz and 2019 Golden State Warriors), but you would probably need to have the best midrange sniper in the game in Kevin Durant to do that. Furthermore, the league average three-point attempts have only continued to increase, so don't expect that to stop anytime soon. Of course, there are plenty of other factors, such as a team's field goal % at the rim or the best offense probably also having the best three-point shooters, that affect offensive rating. Even turnovers also count against offensive rating. However, there is a clear and obvious relationship between offensive performance and three-pointers attempted that simply cannot be ignored.
