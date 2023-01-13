# NFLGamePrediction

## Result

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

Spread win percentage is an interesting calculation that we wanted to take a look into. We created this chart by aggregating
all final scores of games and the how many points the favorite was predicted to win by. We then charted the percentage at
which teams win when favored by each spread in Figure 5. One statistic we wanted to find is if there was a spread that
could be for lack of better words, bad luck. From our calculations, this appears to be 16.5. If a team is favored at 16.5
points, they have less than a 40 percent chance to win. Some of the data points in this figure are what we expected. All
spreads from -10.5 to -1.5 fall around the 50% win rate. We foresaw this outcome as most NFL games feature spreads in
this range

## Future Work
Although the prediction model looks at many different factors useful for predicting games we would like to look into
more factors. There are thousands of different factors that go into why teams win or lose, and we would like to explore more
of these. Some examples could be how teams do at running or passing the ball and how teams do at defending against each
of those. Also how teams do in different weather conditions, or how specific players match up against each other. We would
also like to perform more analysis on how teams do over a span of games. Examples would be how teams do on win/losing
streaks, after a close loss or a big win, after a blowout win/loss, or after long streaks of being home or away. Ideally the
model would have many different factors each weighted based on how much of an impact they have on outcomes and all
of these would be used for each team to determine which team has a net advantage against the spread. Another thing we
would like to add would be a feature that would predict how teams would do in the preseason. There are many available
betting markets preseason that could also be profitable

