# 2025-26 Points per Win
*by Wendel Pericles*

## Introduction

The concept is simple, score the most points and you win the game. But when NBA teams win games, do they score more than their average or do some teams have to reduce thier offensive output and focus on other aspects of the game in order to win? If a team is really good, then the assumption is that they likely blow away most competition with high scoring basketball. Perhaps it may be the other around, poorer teams may need to cultivate more effort than normal to pull out a win. But is that method sustainable?

## Points per Win Vs Overall Average

The graph displays each repspective team's average points per win and there average points per game. There is a black horizontal line to represent the league-wide average points per win so it can be easier to analyze how teams perform against the average. At first glance, the Utah Jazz and the Miami Heat's average points per win stands out the most by being really high. In the case of the Utah Jazz, there overall average points per game is much further below their average points per win compared to the Miami Heat's averages. Another standout is how poor the Brooklyn Nets's average point per win is. Not only does the Nets have the worst average points per win, they also have the worst points per game overall. not even reaching 110 points per game. Both the Jazz and the Nets were one of the worst teams in the league in the 2025-26 NBA season.

![Figure 1](plots/points_per_win.png)

## Utah's Win Performance

![Figure 2](plots/uta_wins_scatter.png)

The Utah Jazz didn't win often throughout the season. But out of the games the Jazz won, there were several games where both teams scored very high. This indicates that the Jazz tended to sacrafice defense in order to produce high-scoring offense to win. This is likely the reason why the Jazz averaged the highest points per win (128.9 per game) in the league and why their win average and overall average had the largest difference in the league (11.3 points). It's not sustainable to maintain such a high offensive output for an entire season, which is likely why the Jazz had a poor win percentage.

## Brooklyn's Win Performance

![Figure 3](plots/bkn_wins_scatter.png)

The Brooklyn Nets had the second highest point differential between points per win and overall points per game (10.4 points). Although the Nets find a way to produce a personal higher than normal offensive efficiency, they averaged the lowest points per win average (116.3 points) and had the leagues worst overall points per game average (105.9). The Nets were the only team to average less than 110 points per game. The Nets' peak offense couldn't rival the league's elite, as their average points per win lagged behind a third of the NBA. Altought victories were sparse, the Nets were able to make up for their lack of offensive output with their defensive performance. In one of their best defensive performace, the Nets managed to smother their opponents with holding them to less than 90 points while scoring an uncharacteristically high 127 points. Unfortunately, the Nets could not make strong defense a regular occurance. They ended the season with only 20 wins, third worst in the league.

## Point Average Differentials vs Win Percentage

The Utah Jazz and the Brooklyn Nets were of the poorer teams in the 2025-26 NBA regular season. When looking back at the 'Points per Win vs Points per Game' bar graph, I noticed that both teams had large gaps between with points per win and points per game averages. When looking at the data for the Oklahoma City Thunder, team with the best record in the league, their gap was much smaller with only 3.2-point gap between their average victory score and overall average.

### OKC's Win Performance

![Figure 4](plots/okc_wins_scatter.png)

The Thunder were led by the back-to-back MVP Shai Gilgeous-Alexander. The team's scatter plot shows that the team was very consistent, not matter the venue. At away games, the Thunder are still able to maintain the high scoring performances. The Thunder also presented themselves as a defensive juggernaut, keeping teams under 100-points 12 times throughout the season. With an efficient offense and a smothering defense, the Thunder were able to go 36-0 when scoring at least 122 points. The team was still able to win plenty of games when scoring less than 122 points. This is proof that the Thunder can adapt to any playing style to win, whether it's high scoring blowouts or low scoring 'grind'em out' games. It is easy to see why the Thunder had the best record in the regular season.

### Point Differential and Winning

After seeing that two of the poorer teams, the Jazz and the Nets, have to score much more than average and the Thunder, best record in the league, don't have to score so high, I began to wonder if this was a trend. After aggregating the data to determine every teams' point differential between points per win average and overall points per game average, and to determine their win percentage, I plotted the results.

| Team   |   Points per Win |   # of Wins |   Points per Game |   Points Differential |   Win Percentage |
|:-------|-----------------:|------------:|------------------:|----------------------:|-----------------:|
| HOU    |           118.31 |          52 |            115.23 |                  3.08 |            0.634 |
| SAS    |           122.95 |          62 |            119.83 |                  3.12 |            0.756 |
| DEN    |           125.3  |          54 |            122.07 |                  3.22 |            0.659 |
| OKC    |           122.27 |          64 |            119.02 |                  3.24 |            0.78  |
| DET    |           121.15 |          60 |            117.77 |                  3.38 |            0.732 |
| CLE    |           124.04 |          52 |            119.52 |                  4.51 |            0.634 |
| MIN    |           123.04 |          49 |            118    |                  5.04 |            0.598 |
| ATL    |           123.52 |          46 |            118.46 |                  5.06 |            0.561 |
| NYK    |           121.75 |          53 |            116.45 |                  5.3  |            0.646 |
| BOS    |           120.45 |          56 |            114.85 |                  5.59 |            0.683 |
| CHA    |           121.8  |          44 |            116.01 |                  5.78 |            0.537 |
| LAL    |           122.62 |          53 |            116.34 |                  6.28 |            0.646 |
| PHX    |           118.89 |          45 |            112.59 |                  6.3  |            0.549 |
| TOR    |           121.02 |          46 |            114.63 |                  6.39 |            0.561 |
| ORL    |           122.29 |          45 |            115.74 |                  6.54 |            0.549 |
| POR    |           122.07 |          42 |            115.48 |                  6.6  |            0.512 |
| PHI    |           122.51 |          45 |            115.88 |                  6.63 |            0.549 |
| MEM    |           121.4  |          25 |            114.67 |                  6.73 |            0.305 |
| LAC    |           120.6  |          42 |            113.77 |                  6.83 |            0.512 |
| MIA    |           127.77 |          43 |            120.87 |                  6.9  |            0.524 |
| GSW    |           121.68 |          37 |            114.61 |                  7.07 |            0.451 |
| NOP    |           123.88 |          26 |            115.52 |                  8.36 |            0.317 |
| WAS    |           121.47 |          17 |            112.9  |                  8.57 |            0.207 |
| CHI    |           125    |          31 |            116.3  |                  8.7  |            0.378 |
| IND    |           121.21 |          19 |            112.43 |                  8.78 |            0.232 |
| DAL    |           122.92 |          26 |            114.12 |                  8.8  |            0.317 |
| SAC    |           121.05 |          22 |            111    |                 10.05 |            0.268 |
| MIL    |           120.91 |          32 |            110.63 |                 10.27 |            0.39  |
| BKN    |           116.3  |          20 |            105.93 |                 10.37 |            0.244 |
| UTA    |           128.86 |          22 |            117.59 |                 11.28 |            0.268 |

![Figure 5](plots/win_pct_vs_avg_diff.png)

It was immediately clear that the more points above average a team needs to score, the poorer the winning percentage. The three 60-win teams, the Thunder, Spurs, and Pistons only had to score and extra 3 points, or roughly one shot, in order to win thier game. On the opposite end, poorer teams, like the Jazz, Nets, and Wizards had to be very uncharacteristic to win their games, and that is not sustainable for an entire season, hence the poor records.