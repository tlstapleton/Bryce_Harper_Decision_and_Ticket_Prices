# Bryce Harper & Ticket Prices

In late February of 2019 (February 25), with Spring Training already begun, Bryce Harper, perhaps the biggest free agent of the 2018-2019 offseason, remains unsigned.
Currently, rumors indicate that the Philadelphia Philles are a strong contender.  Other teams in the mix are the Dodgers, Giants, Padres, and Nationals, to varying degrees.

The question I am looking at is how will Harper's decision influence ticket prices for the 2019 season.  I used the SeatGeek API to pull the median ticket price for every Washington Nationals, Philadelphia Phillies, and LA Dodgers game as of February 2019, before any Bryce Harper decision has been announced.

## February 2019 - Before Bryce Harper Decision
As of February 25, 2019, pre-Bryce Harper Decision Day, this is how ticket prices look for the 2019 season:

### Timeseries of All Games

The below graphs show the timeseries change of median ticket prices for all 2019 season and spring training 
games for each of the three teams: Washington Nationals, Philadelphia Phillis, and the Los Angeles Dodgers.
The green vertical line denotes Opening Day, which shows an expected spike in median ticket price for all teams. 

![Nats All Games](/Images/nats_all_games.png)

![Phils All Games](/Images/phils_all_games.png)

![Dodgers All Games](/Images/dodgers_all_games.png)

### Ticket Prices by Opponent

If we look at the average of the median ticket price of all games for each of the three teams grouped by opponent, we can see that certain opponents command significantly higher ticket prices than others.  In addition, these opponents differ from team to team.

Of the 10 Nationals games with the highest median ticket price on SeatGeek, 2 are Opening Day games (one at Nationals Park and one at
the New York Mets' Citi Field).  In addition, 4 of the games are against the Chicago Cubs, with 3 of the 4 being played in Chicago.  
One of the top 10 games is agains the Baltimore Orioles, otherwise known as the Battle of the Beltway.  All other games are against other teams in the NL East.

![Nats All Opponents](/Images/nats_allopponents.png)

Of the 10 Phillies games with the highest median ticket price on SeatGeek, the highest ticket price is currently tied between Opening Day in Philadelphia and a Phillies away game in Washington, D.C. against the Nationals.
The Boston Red Sox take 4 of the top 10 games by mediant ticket price by opponent.

![Phils All Opponents](/Images/phils_allopponents.png)

Of the 10 Dodgers games with the highest median ticket price on SeatGeek, 2 are Opening Day games (one at Dodger Stadium and one against the Colorado Rockies).
The New York Yankees and the Boston Red Sox combine for 6 games of the Dodgers top 10 games with the highest median ticket price.

![Dodgers All Opponents](/Images/dodgers_allopponents.png)

### Ticket Price for Home Games 

What opponents command the highest ticket prices at each team's home ballpark?  

For the Nationals, the Philadelphia Phillies command the highest ticket prices at Nationals Park on Seatgeek currently.  Will this change if Bryce Harper goes to the Phillies?  Will the local fans still flock to see a former hometown hero?  Or will they be turned off by
a player who took his talents up 95 to a team in the same division?

![Nats Home Games](/Images/nats_homeopponents.png)

The highest median ticket prices at Citizens Bank Park can be found when the Phillies play the reigning World Series Champs, the Boston Red Sox.

![Phils Home Games](/Images/phils_homeopponents.png)

In L.A., the New York Yankees coming to town results in the highest median ticket prices.  Apparently in L.A., they love star power.

![Dodgers Home Games](/Images/dodgers_homeopponents.png)

### Ticket Price for Away Games 

Where do these teams command the highest ticket prices when they are on the road?

For the Nationals, it appears that Wrigley Field is at the top of the list.  The Nationals at Cubs games currently have the highest average median ticket price
listed on SeatGeek for Nationals away games.  Who are the next three top contenders?  The Orioles, Dodgers, and Phillies, in that order.  

![Nats Away Games](/Images/nats_awayopponents.png)

When the Phillies go on the road, their ticket prices are highest when they are in Fenway Park.  Their games in D.C. rank 4th.

![Phils Away Games](/Images/phils_awayopponents.png)

Once again, Boston comes in at the top when the L.A. Dodgers are away as well.

![Dodgers Away Games](/Images/dodgers_awayopponents.png)

## Conclusions Pre-Harper Decision

* The top median ticket price currently on SeatGeek for each of the three teams is, unsurprisingly, each team's respective home opener.

* Also not the most surprising, the Boston Red Sox command high ticket prices.  As the reigning World Champs, this is probably to be expected.  In fact, ticket prices are most likely naturally higher at Fenway Park than other stadiums, regardless of the opponent.

* Another thing to note: the Cubs continue to bring in high ticket prices even 3 years after their historic World Series win.  Especially in D.C., where the Nationals and Cubs, although in different divisions, have in past seasons had some exciting games.

* Although it may be true that teams such as the Cubs and Red Sox have higher ticket prices in their home stadiums regardless of opponent, it will be interesting to see if Bryce Harper's decision makes these prices go up or down relative to how they currently stand, before his decision.

# March 2019 - After Bryce Harper Decision

## The Decision

On February 28, 2019 at approximately 1:50pm, news broke that the Philadelphia Phillies were going to sign Bryce Harper to a 13-year, $330 million dollar deal.
After collecting the median ticket price for Phillies Opening Day as they stood on SeatGeek on February 25, February 26, and February 27, I also collected the median ticket price at every hour for 24 hours after the Bryce Harper news broke.  The week of the decision, the median ticket price wavered between $165 and $180 before the news broke.


![](/Images/Phillies_GIF.gif)

At February 28th on 2pm, just as news was breaking about Bryce Harper joining the Phillies, the median ticket price on SeatGeek for the Phillies' Home Opener was $175.  An hour later, the median ticket price was $234, a 33.7% increase. 