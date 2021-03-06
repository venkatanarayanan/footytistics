---
layout: post
title: Different data visualizations I have create in R
subtitle: Football Visualizations
image: /img/soccer-ball-variant.png
tags: [Visualizations]
---

In this article I explain the different data visualizations I have created using R programming. I have mostly used R's ggplot package to create these visualizations.

The Bundesliga was the first big 5 european league to restart post lockdown and came to a close on 27th June, 2020. Bayern Munich won the league title for a record 8th successive year and finished 12 points above their closest challengers Borrusia Dortmund. The Champions also had the third youngest squad in terms of mean age.

![bundesliga-1920-age-profile](/img/bundesliga_1920/bun_teams_age_profile_1920.png)

# Spurs Pressing vs Everton

Jose Mourinho's teams are usually known for defending deep and counter-attacking. In the first league game of the 2020/21 season, Mourinho's Tottenham welcomed Carlo Ancelloti's Everton. There was an article in [The Athletic](https://theathletic.com/2065743/2020/09/15/mourinho-lazy-pressure-pressing-analysis/?redirected=1) discussing about Spurs' pressing from that game. I tried to recreate one passing sequence of Everton that shows Spurs' disorganized Pressing and Everton playing out from the back.

![spurs-pressing-v-everton](/img/epl_2021/spurs_press.gif)

The above gif was created using gganimate and the code can be found [here](https://github.com/venkatanarayanan/football-animated-plots/tree/master/Spurs_Everton_13092020)

# Visualizing the Marcus Rashford and Daniel James partnership in Premier League 2019/20

Manchester United signed Daniel James from Swansea City in the summer of 2019. James scored in three of his first four league games as a Manchester United player but his form slowly detoriated over the course of the season and he did not score after that. However, he ended the season with 6 assists, only behind Marcus Rashford & January signing Bruno Fernandes. Four of his six assists in the league came for Marcus Rashford. Here is a visualization I created to revisit their the goals assisted by Daniel James for Marcus Rashford.

![rashford_james_partnership](/img/epl_1920/rashford_james_partnership.png)
