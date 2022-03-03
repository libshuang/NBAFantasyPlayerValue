# NBA Fantasy Player Value Projections

### Project Authors
- Libin Huang | <u>[LinkedIn](https://www.linkedin.com/in/libinh/)</u>

---

### Table of contents
- <u>[Problem Statement](#Problem-Statement-and-Key-Objective)</u>
- <u>[Findings](#Findings)</u>

---

### Problem Statement and Key Objective

<b> Context </b>

There's countless ends of fantasy sport articles and projections that provides the very similar values as mines. 
My projections is to be as risk adverse to the random events (e.g. injuries, COVID protocols, mid-season rotational changes, trades) as possible by using prior historical boxscores and numbers of games played,  as well as last year's team record.

According to an ESPN article written by Braxter Holmes, there were 2,909 games lost to soft-tissue injuries during the 2020-21 season. It's the second-highest figuresince 2005-06. The most was 3,038 in the 2017-18 season, which was played in 82 games vs. the 72-game campaign this year.

The increase was even more pronounced when focusing on the league's stars. This season's All-Stars missed 370 of a possible 1,944 games (19%), the highest percentage in a season in NBA history, according to Elias Sports Bureau research. They missed an average of 13.7 regular-season games each this year. All in all, the injury count is far too high to be ignored, and must be a valuating factor in deciding in real life games, and in fantasy sports.

Trades have also significantly increased as well. 2021-22 season comprised of 35 players, and 2020-21 had the most players moved the last decade: 48 players. In a player driven league now, being unable to meet expectations and a team reset is becoming more of a norm. Understanding player salary and past team records can help predict future moves within an NBA franchise.


<b> Key Objective </b>
- Rank Players based on Past Historical Boxscores, Team Record (for stability), salary (more $, more years left on contract means more overall minutes), and Injury History
- Adjust all the Percentage Weights (FG%, FT%, and 3PT%) based on volume
---

### Data Dictionary
| Column | Description |
| --- | --- |
| **Points** | Points |
| **Assists** | Assists |
| **Rebounds** | Rebounds |
| **Steals** | Steals |
| **Blocks** | Blocks |
| **ToV** | Turnovers |
| **FG%_Adj** | Field Goal %, adjusted |
| **FT%_Adj** | Free Throw %, adjusted |
| **3PT%_Adj** | Field Goal %, adjusted |


---

### Sources
1. https://www.basketball-reference.com
2. https://www.nba.com
