![image](https://github.com/stonedmonk-e/sqlzoo_solutions/assets/111871083/7cf5d460-9c94-4468-ba42-859096b5fefd)

## Tables
![image](https://github.com/stonedmonk-e/sqlzoo_solutions/assets/111871083/394de742-914c-4d1c-aee3-2fe1fc2b3dbd)


### Question 1
To show the matchid and player name for all goals scored by Germany

SELECT matchid, player FROM goal 
  WHERE teamid = 'GER';


### Question 2
Show id, stadium, team1, team2 for just game 1012

SELECT id,stadium,team1,team2
  FROM game WHERE id = 1012


