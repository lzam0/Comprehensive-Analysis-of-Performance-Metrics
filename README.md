# Comparative Analysis of Performance Metrics: UCLA vs. Hawaii Men's Volleyball 2023 Season!

## Abstract
Volleyball demands individual skill, strategy, and teamwork for success. Teams like Hawaii and UCLA excel at collegiate levels, demonstrating talent and competitive spirit. This poster delves into statistical analysis of UCLA and Hawaii Men's Volleyball teams in the 2023 season, examining player metrics, match outcomes, and overall team performance to identify key success factors.

## Key Terms
- A kill is defined as: A kill (K) is awarded to a player any time an attack is unreturnable by the opposition and is a direct cause of the opponent not returning the ball, or any time the attack leads directly to a blocking error by the opposition.
- A dig is defined as a controlled pass of a hard driven ball coming from the opponent's attack, usually a spike or a serve.
- 5-1 Rotation – 5 attackers and 1 setter

- Positions:
  -	Outside Hitter (OH)
  -	Opposite Hitter (OPP)
  -	Middle Blocker (MB)
  -	Setter (S)
  -	Libero (L)
  -	Defensive Specialist (DS)

## Data Collection
I initially thought of investigating Volleyball England Super League statistics; however the website did not provide team sheets of players. However, I opted to examine the NCAA final contenders, UCLA and Hawaii, of the 2023 volleyball championship. This match matchup was eagerly awaited as one of the highlights of the 2023 season.
Data link sources: https://stats.ncaa.org/team/110/stats/16380 , https://stats.ncaa.org/team/277/stats/16380
I manually scraped data (copied and pasted fields), such as player name, jersey number, height, etc... I decided that using two teams roster data was sufficient as I wanted to compare both teams against each other. This process was painfully long as initially I wanted to scrape the data using a python program to grab the data from the website tables. The NCAA website has a data protection policy, and I did not want to break the policy through scraping the data. Some fields were null values, resulting in incorrect csv formatting, which required me to alter the csv until it was accurate to the table on the website. When importing the csv into my program, I filled null values with 0 as a placeholder and discarded player data when necessary. 
