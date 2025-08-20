# INDIAN-PREMIER-LEAGUE-(IPL)-2008_2019
<img width="975" height="549" alt="image" src="https://github.com/user-attachments/assets/2f70b0d2-09fd-421b-a937-6c52a4d8f43b" />

# INTRODUCTION

 Cricket, often dubbed as a religion at some parts of the world, has evolved beyond being just a sport into global phenomenon, within this   vast cricketing landscape, the Indian premier league stands out as s unique spectacle, blending athleticism, entertainment, and high-       stakes competition.
 The IPL is a cash-rich decade old electrifying cricket league organized by the Board of Control for Cricket in India (BCCI) in 2007 and     played out in India for the from 2008 onwards. It has made its impact globally and one of the most celebrated Cricketing Leagues around     the Cricketing World. 
It is the most attended cricket league in the world and rank sixth among all sports. The IPL has witnessed remarkable growth and its value   soaring from $2 billion USD in 2009 to staggering $5.7 billion USD in 2019. The Members of BCCI also believed the league as one of the      best platforms to find talent for the national Team.

# PROJECT OVERVIEW
 This project delves into the analysis of the Indian premier league (IPL) twenty over(T20) cricket Tournament match data spanning from 2008 to 2019.
  The primary focus of this analysis aims to analyze players performance and Team statistics including runs scored, wickets taken and match winning Performances and Outcomes.

 # STEP 1: DATA IMPORTING
  Firstly, all the necessary libraries needed for data cleaning/handling, visualization and Model building were imported.

 # STEP 2: LOADING THE DATA/DATA SOURCES
  The dataset was loaded in an Excel Workbook as a CSV (comma separated values) file and its structures examined.
  The dataset consists of six (6) tables which has different columns attached to them;

 ## 1.	TABLE 1: Players which contains the following columns;
 1. Player-Name
 2. Date of Birth (DOB)
 3. Battling-hand
 4. Bowling-skill
 5. Country

## 2.	TABLE 2: Deliveries which has the following 21 columns;
 1.	Match-id
 2.	Inning
 3.	Battling team
 4.	Bowling team
 5.	Over
 6.	Ball
 7.	Batsman
 8.	Non-striker
 9.	Bowler
 10.	Is-super-over
 11.	Wide-runs
 12.	Bye-runs
 13.	Leg bye-run
 14.	No-ball-run
 15.	Penalty-runs
 16.	Batsman-run
 17.	Extra-run
 18.	Total-runs
 19.	Player-dismissed
 20.	Dismissal-kind
 21.	Fielder

## 3.	TABLE 3: Matches; under here, there are 17 columns of which there are missing values in at least 1 column, and they are listed below;
 1. Id
 2. Season
 3. City
 4. Date
 5. Team 1
 6. Team 2
 7. Toss-win
 8. Toss-decision
 9. Result
 10. Dl-applied
 11. Winner
 12. Win-by-runs
 13. Win-by-wickets
 14. Player of match
 15. Venue
 16. Ump2ire 1
 17. Umpire 2
 18. Umpire 3

## 4.	TABLE 4: Teams; this contains the overall names of teams in the dataset.

## 5.	TABLE 5: Teamwise-home-and-away; there are 7 columns here which are;
 1. Team
 2. Home-wins
 3. Away-wins
 4. Home-Match
 5. Away-Match
 6. Home-win-percentage
 7. Away-win-percentage

## TABLE 6: Most-Runs-Average-Strike rate; under this table, there are 6 columns which are as follows;
  1. Batsman
  2. Total-runs
  3. Out
  4. Number of balls
  5. Average
  6. Strike rate

## Dataset source: https://www.kaggle.com/datasets/ramjidoolla/ipl-data-set

# STEP 3: TOOLS USED
 The following tools were used to analyze the dataset;

  1. Microsoft Excel
  2. SQL (Standard Query Language)
  3. Power Bi Desktop (PBIX)

# STEP 4: DATA CLEANING
 The dataset appeared to be cleaned and processed already and didn’t need to go through all of the alterations as there were no duplicated variables and null rows allowed for the datasets.

# STEP 5: EXPLORATORY DATA ANALYSIS (EDA)
 The IPL (Indian Premier League) dataset contains lots of information about different Seasons, Teams, Players, Matches and Venue. It’s like a big treasure chest waiting to be explored, with Exploratory Data Analysis, the aim is to dig into the dataset to uncover insights, patterns and stories hidden within and what makes it so exciting.

 The following questions were queried to uncover the hidden stories and patterns in the dataset:
 1.	How many Teams competed in the Indian Premier League between 2008-2019 Match? 	
 2.	How many Countries made up the teams?
 3.	Determine the top 5 teams with highest Total-Run, Home-Win-Percentage and Away-Win Percentage
 4.	Determine the player with the overall Strike-Rate
 5.	Determine the team’s performance ranking
 6.	In the Toss-decision, which one was prevalent? Bat or field
 7.	Does winning the toss give more chances to winning the match?
 8.	Which team won most games?
 9.	mention the top 10 players from the dataset according to their wins and runs.
 10.	 What is the most common win type from the dataset?
 11.	which team played most of the matches?
 12.	which season had the highest runs scored and wicket taken?

