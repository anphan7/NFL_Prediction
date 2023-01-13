# NFLGamePrediction

![image](https://github.com/anphan7/NFL_Prediction/blob/main/Graphs/Win%20Margin%20Frequency.png)

The first thing that we wanted to look into was common win margins. For each game common betting markets are the moneyline (who wins the game) and the spread (how many points a team wins by). In order to decide which spreads to take it is important to know common amounts of points games are won by. From the graph below it can be seen that the most common win margins are 3 points 7 points 6 points 10 points and 14 points. This knowledge would be useful for deciding whether to take an alternate spread or to bet on a team you might not otherwise think will cover. If you think the favorite is likely to win but the spread is -7.5 it might be a good idea to either take -5.5 at a reduced payout because 6 and 7 points are very common win margins, or if you are feeling bold you could take -9.5 because not many games are decided by 8 or 9 points.

![image](https://github.com/anphan7/NFL_Prediction/blob/main/Graphs/Rivalry%20Spread%20Margin%20Frequency.png)
![image](https://github.com/anphan7/NFL_Prediction/blob/main/Graphs/Non%20Rival%20Spread%20Margin%20Frequency.png)

In the NFL, there are a number of significant rivalries between teams. Rivalries are sometimes formed as a result of a
specific event that causes bad blood between players or teams. Rivalries in the NFL are widely recognized by both fans and
players. Whenever a rivalry game happens, it is hard to predict accurately who will win the game. In figure 2, we took the
divisional rivals throughout the NFL and compared the winning margin against the spread between those two rival teams.
As a result, the average is 0.0196 points above Vegas’s spread for the rival game. This shows that Vegas on average is
very good at setting the spreads for rivalry games. However that does not mean that looking at rivalry games is useless. As
Figure 3 shows, for the games that are not rivalry games the underdog covers by an average of 0.3 points. This leads to the
conclusion that underdogs cover the spread more often than not in all games except rivalry games.

![image](https://github.com/anphan7/NFL_Prediction/blob/main/Graphs/Home%20Field%20Spread%20Advantage.png)

Another major factor we were interested in studying is home field advantage. It is well known that for a variety of reasons
the home team has an advantage in a football game. However quantifying this advantage for each team was of great interest.
Figure 4 shows the results of this analysis. These values were calculated by calculating the average spread win margin for
each team both at home and away and subtracting the away average from the home average. Teams with a positive number
have a stronger home field advantage than Vegas expects, and teams with a negative number have a weaker home field
advantage than Vegas expects. This means that if a team has a high number it would likely be beneficial to bet on them to
cover at home.

![image](https://github.com/anphan7/NFL_Prediction/blob/main/Graphs/Screen_Shot_2022-12-05_at_7.16.08_PM.png)
