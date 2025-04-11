# Producing_Soccer_Insights_for_a_Sports_Media_Agency
Producing Soccer Insights for a Sports Media Agency

The UEFA Champions League, often called the Champions League, is a preeminent annual soccer competition that captivates fans worldwide. Established in 1955 as the European Champion Clubs' Cup, it evolved into the UEFA Champions League in 1992, broadening its appeal. The modern format features 32 top-tier club teams selected based on their domestic league performance, adding to the intrigue.


![Stadium.jpg](Stadium.jpg)


This electrifying event transcends sports, becoming a celebration of unity, culture, and national pride. Fans, draped in their countries' colors, create an electric atmosphere, making the tournament as much about the spectators as the players.Financially, the Champions League is a lifeline for clubs, boosting revenues and offering transformative opportunities. Nevertheless, it sparks debates about wealth disparities in European soccer.



![Duel_football](Duel_football.jpg)

The Champions League is synonymous with historic rivalries, underdog triumphs, and individual brilliance. For players, it represents a career pinnacle, while for fans, it's a cultural phenomenon. The iconic anthem and rituals enrich the soccer experience. In 200 words, the UEFA Champions League is the epitome of European soccer excellence, offering unforgettable moments, financial rewards, and a unique cultural impact, with 32 top clubs adding to its allure.






## Schema name: `SOCCER`
## Table Name(s): `TBL_UEFA_2020` | `TBL_UEFA_2021` | `TBL_UEFA_2022`
### Note : All three tables have same column names and data types

| Column | Definition | Data type |
|--------|------------|-----------|
| `STAGE`| Stage of the March | `VARCHAR(50)` |
| `DATE` | When the match occurred. | `DATE` |
| `PENS` | Did the match end with penalty | `VARCHAR(50)` |
| `PENS_HOME_SCORE` | In case of penalty, score by home team | `VARCHAR(50)` |
| `PENS_AWAY_SCORE` | In case of penalty, score by away team | `VARCHAR(50)` |
| `TEAM_NAME_HOME` | Team home name | `VARCHAR(50)` |
| `TEAM_NAME_AWAY`| Team away  name | `VARCHAR(50)` |
| `TEAM_HOME_SCORE` | Team home score | `NUMBER` |
| `TEAM_AWAY_SCORE` | Team away score | `NUMBER` |
| `POSSESSION_HOME` | Ball possession for the home team | `FLOAT` |
| `POSSESSION_AWAY` | Ball possession for the away team | `FLOAT` |
| `TOTAL_SHOTS_HOME` | Number of shots by the home team | `NUMBER` |
| `TOTAL_SHOTS_AWAY` | Number of shots by the away team | `NUMBER`
| `SHOTS_ON_TARGET_HOME` | Total shot for home team | `FLOAT` |
| `SHOTS_ON_TARGET_AWAY` | Total shot for away team | `FLOAT` |
| `DUELS_WON_HOME` | duel win possession of ball - for home team | `NUMBER` |
| `DUELS_WON_AWAY` | duel win possession of ball - for away team | `NUMBER` 
| `PREDICTION_TEAM_HOME_WIN` | Probability of home team to win | `FLOAT` |
| `PREDICTION_DRAW` | Probability of draw | `FLOAT` |
| `PREDICTION_TEAM_AWAY_WIN` | Probability of away team to win | `FLOAT` |
| `LOCATION` | Stadium where the match was held | `VARCHAR(50)` | 

Note that *in Snowflake all databases, tables, and columns are **upper case*** by default.

You will execute SQL queries to answer three questions, as listed in the instructions.
