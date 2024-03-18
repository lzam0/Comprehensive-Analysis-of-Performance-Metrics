# Comparative Analysis of Performance Metrics: UCLA vs. Hawaii Men's Volleyball 2023 Season!

Comparative Analysis of Performance Metrics: UCLA vs. Hawaii Men's Volleyball 2023 Season
Written By Leihl Zambrano
Abstract
Volleyball demands individual skill, strategy, and teamwork for success. Teams like Hawaii and UCLA excel at collegiate levels, demonstrating talent and competitive spirit. This poster delves into statistical analysis of UCLA and Hawaii Men's Volleyball teams in the 2023 season, examining player metrics, match outcomes, and overall team performance to identify key success factors.
Key Terms
•	A kill is defined as: A kill (K) is awarded to a player any time an attack is unreturnable by the opposition and is a direct cause of the opponent not returning the ball, or any time the attack leads directly to a blocking error by the opposition.
•	A dig is defined as a controlled pass of a hard driven ball coming from the opponent's attack, usually a spike or a serve.
•	5-1 Rotation – 5 attackers and 1 setter
•	Positions
-	Outside Hitter (OH)
-	Opposite Hitter (OPP)
-	Middle Blocker (MB)
-	Setter (S)
-	Libero (L)
-	Defensive Specialist (DS)
Data Collection
I initially thought of investigating Volleyball England Super League statistics; however the website did not provide team sheets of players. However, I opted to examine the NCAA final contenders, UCLA and Hawaii, of the 2023 volleyball championship. This match matchup was eagerly awaited as one of the highlights of the 2023 season.
Data link sources: https://stats.ncaa.org/team/110/stats/16380 , https://stats.ncaa.org/team/277/stats/16380
I manually scraped data (copied and pasted fields), such as player name, jersey number, height, etc... I decided that using two teams roster data was sufficient as I wanted to compare both teams against each other. This process was painfully long as initially I wanted to scrape the data using a python program to grab the data from the website tables. The NCAA website has a data protection policy, and I did not want to break the policy through scraping the data. Some fields were null values, resulting in incorrect csv formatting, which required me to alter the csv until it was accurate to the table on the website. When importing the csv into my program, I filled null values with 0 as a placeholder and discarded player data when necessary. 
Data Analysis
Through this project, I aim to investigate the performance metrics of both teams, focusing on both team and individual player performance. As renowned contenders in the D1 collegiate level, UCLA and Hawaii offer valuable insights into various aspects of the game. Key metrics such as passing/digging, position kills, player heights, team synergy, and other factors will be examined to identify similarities and patterns in their performance.
Player Height Analysis
Height is a critical factor in volleyball, influencing players’ effectiveness in various positions on the court. In this comparative analysis, we delve into the height distribution of players across different positions of Hawaii and UCLA. I modified the initial data so that positions L and DS are combined so that there would be some consistency between both teams. (UCLA does not have a DS). Furthermore, I modified height data so that values were shown in cm rather than ft, so that exact values can be easier to understand.
 
Figure 1Comparative Box Plot Analysis: Height Distribution of Positions in UCLA and Hawaii
Through this visualisation, we can see a range of heights of each position between both teams
 
Figure 2 Height Table Between Hawaii and UCLA
Player Passing/ Digs Analysis
Passing is the first contact of the volleyball, after the ball has passed the opponents’ side of court. A well-executed pass can allow a team to set up offensive play, to effectively allow the team to generate a point. The accuracy of the pass can be broken down into 3 categories, 3 attacker, 2 attacker, 1 attacker passes. These terms denote the options available to the setter after a successful pass: 3 attacker passes allow the setter to choose from all three front-row hitters, 2 attacker passes limit the options to two hitters, and 1 attacker passes offer only one hitter as a potential option. Notably, the data that has been collected focuses solely on individual passing metrics, excluding the accuracy of the dig.
 
Figure 3 Comparative Bar Graph Analysis: Passing Metrics
Through Figure 2’s visualization, the green bar shows us Hawaii performance in digging/ passing throughout the season. Blue bar shows us UCLA performance in digging/ passing throughout the season. Both show that the Libero position obtaining the most digs singlehandedly. However, the outside hitter digging totals are greater than the libero. This is because there are 2 OH in the 5-1 rotation. Exploring the digging totals of each team, UCLA has a total of 907 and Hawaii has a total of 944. The total between both teams is 1851.
This data is interesting because Hawaii has a 2% better defense than UCLA. This could suggest that Hawaii keeps more balls in play during each set, mentally frustrating opponents’ offense and possible enabling more opportunities for a counterattack.
Player Kill Analysis
Another metric that would be interesting to investigate would be the kills of induvial players throughout the season. With this data, we can observe player kills and errors, analyse the team's setting distribution, and assess attacking efficiency. Comparing each team will enable us to identify trends across the two teams.
 
Figure 4 Comparative Offensive Points Analysis
In this figure, I decided to remove positions L/DS as those kills were not valid 
The data presented in Figure [Number] illustrates the kill statistics for both Hawaii and UCLA. The green bar represents Hawaii's successful attacking performance, while the blue bar denotes UCLA's successful attacks. Additionally, error bars coloured in purple and orange represent the attacking errors made by each team. Some observations to take note is that Hawaii has a lower kill total compared to UCLA. This is significant as this could suggest that UCLA’s offence performs better overall compared to Hawaii.
  
Figure 5 Comparative Pie Chart Analysis

Another noteworthy observation is that UCLA and Hawaii each have key hitters who contribute the highest attacking points to their teams compared to other positions. Hawaii offence revolves in utilising all hitters available, as seen in the pie chart of kills. However, the data suggests that Dimitrios Mouchlias (OPP) is a key part of Hawaii’s dynamics and offensive strategy, as he boasts a 19% higher success rate in attacks compared to the next highest offensive scorer. 
Though Hawaii’s attacking performance shows that the oppo hitter has the highest individual kill total, the position that scored the highest overall total of points through offence is the outside hitters with a 44.5% team attacking total. With both outside and opposite hitters posing a threat to the front court blockers of opposing teams, it could result in more one-on-one blocks attempts, resulting in an outstanding offensive total.
Alternatively, UCLA primarily relies on their OH for offensive points, indicating that the team offensive statistics are centered on high level, smart OH in a high number of scoring chances, accounting for 84.4% of their scoring opportunities. This implies that UCLA OH excels in generating points on the front and back court. One potential reason for OH’s higher kill rate could be attributed to the lower passing percentage, therefore, reducing opportunities for the MB and OPP to attack.
Conclusion
In conclusion, this investigation into the performance metrics of the UCLA and Hawaii Men’s Volleyball team during 2023 season contains valuable insight of key success elements. Through a comprehensive analysis of player and overall team performance with the use of data science, several key factors have emerged. We first investigated player heights across each position. Additionally, examined the passing and digging, along with offensive strategies within both teams. demonstrating a slightly superior defensive prowess and UCLA showcasing a more focused offensive strategy.
Furthermore, our analysis covered significant players such as Dimitrios Mouchlias from Hawaii, whose performance on court, aid team Hawaii in strengthening their offence. From what we have observed, volleyball is a combination of individual success, team chemistry and strategic adaptability. As the sport continuing to evolve, this investigation informs enthusiasts like myself but also provide valuable knowledge for players, coaches and analysists worldwide. Using data science, we can obtain a greater deeper understanding and appreciation of the sport.
Possible Improvements on Project
-	Investigate into height metrics
-	Investigate into serving metrics (Key factor on gaining a point)
-	Investigate into passing metrics further
References
1.	UCLA Data: https://stats.ncaa.org/team/110/stats/16380
2.	Hawaii Data: https://stats.ncaa.org/team/277/stats/16380
3.	What is a dig/ pass? https://volleyballadvisor.com/what-is-a-dig-in-volleyball/#:~:text=Definition%20of%20a%20dig,-In%20my%20experience&text=A%20dig%20is%20defined%20as,to%20set%20up%20a%20counterattack.
4.	What is a kill? NCAA rules (article 2) http://fs.ncaa.org/Docs/stats/Stats_Manuals/VB/2008%20VB%20Stats%20Manual%20easy%20print.pdf
5.	What is kill? NCAA article 2020 https://www.ncaa.com/news/volleyball-women/article/2020-07-14/college-volleyball-dictionary-glossary-and-terms-everything-you-need-know
6.	What is a kill error? NCAA rules (article 3) http://fs.ncaa.org/Docs/stats/Stats_Manuals/VB/2008%20VB%20Stats%20Manual%20easy%20print.pdf
7.	Can a Libero Kill a volleyball? https://goldmedalsquared.com/post/what-is-a-libero-in-volleyball/#:~:text=A%20libero%20is%20not%20allowed,happen%20from%20time%20to%20time.


