Content This dataset includes 44,341 results of international football matches starting from the very first official match in 1872 up to 2023. The matches range from FIFA World Cup to FIFI Wild Cup to regular friendly matches. The matches are strictly men's full internationals and the data does not include Olympic Games or matches where at least one of the teams was the nation's B-team, U-23 or a league select team.

# Football Match Data

## Results Dataset

| Column       | Explanation                                                |
| ------------ | ---------------------------------------------------------- |
| date         | Date of the match.                                         |
| home_team    | Name of the home team.                                     |
| away_team    | Name of the away team.                                     |
| home_score   | Full-time home team score including extra time, not including penalty-shootouts. |
| away_score   | Full-time away team score including extra time, not including penalty-shootouts. |
| tournament   | Name of the tournament.                                    |
| city         | Name of the city/town/administrative unit where the match was played. |
| country      | Name of the country where the match was played.            |
| neutral      | TRUE/FALSE column indicating whether the match was played at a neutral venue. |

## Goalscorers Dataset

| Column   | Explanation                                                |
| -------- | ---------------------------------------------------------- |
| date     | Date of the match.                                         |
| home_team| Name of the home team.                                     |
| away_team| Name of the away team.                                     |
| team     | Name of the team scoring the goal.                         |
| scorer   | Name of the player scoring the goal.                       |
| own_goal | Whether the goal was an own-goal.                          |
| penalty  | Whether the goal was a penalty.                            |
