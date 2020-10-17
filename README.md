# flickr-hackathon-2020
The objective of the problem statement is to predict Total runs of a player in IPL 2020. The
output file should contain only Player Name and the respective IPL 2020 for the test data.

The variables in the train and test data are-
1)PLAYER	-Name of the player
2)Mat	-Matches played in IPL 2018
3)Inns	-Innings batted in IPL 2018
4)NO	-Number of Not Outs in IPL 2018
5)2018_Runs	-Total Runs in IPL 2018
6)HS-	Highest Score in IPL 2018
7)Avg	-Batting Average in IPL 2018
8)BF	-Total Balls Faced in the tournament
9)SR	-Strike Rate in IPL 2018
10)100	-Number of centuries in IPL 2018
11)50	-Number of Fifties in IPL 2018
12)4s	-Number of Fours hit in IPL 2018
13)6s	-Number of Sixes hit in IPL 2018
14)2019_Runs	-Total Runs in IPL 2019

The missing values in the Avg column in the train and test data has been filled as (2018_Runs/Inns) and (2019_Runs/Inns) respectively.Mean value imputation was avoided because of the small number of training examples.
