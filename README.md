# Elite-XI-T20-Squad-Builder
Elite XI T20 Sqaud Builder Python -Powered Player Selection and Power BI Dashboard

Problem Statement:
      Developing a T20 cricket team capable of consistently scoring 180+ runs while defending 150+ runs on average poses a multifaceted challenge that requires a comprehensive strategic approach. This endeavor necessitates the identification and selection of players with exceptional batting prowess, bowling variations, and fielding agility tailored to the dynamic demands of the T20 format. The primary objective is to create a formidable team that not only possesses the firepower to post formidable totals but also exhibits the tactical acumen and resilience to effectively defend challenging targets against formidable opponents. The solution should encompass a cohesive blend of batting order optimization, bowling rotations, fielding positions, and overall tactical strategies meticulously crafted to maximize the team's performance and ensure consistent success in T20 cricket.
1.	Scoring Capability: The team consistently scores 180+ runs on average.
2.	Defensive Capability: The team effectively defends totals of 150+ runs on average.

Strategic Plan for Optimal Performance in T20 Cricket :

-	Utilized Python and Power BI to develop a system for selecting the top 11 T20 cricket players worldwide.
-	Leveraged Pandas and NumPy libraries in Python for efficient data sorting and filtering.
-	Implemented DAX and various Power BI functions to create an intuitive and visually appealing dashboard interface.
-	Demonstrated proficiency in data manipulation, visualization, and problem-solving within sports analytics.
-	Contributed to structured decision-making processes through systematic data analysis and visualization techniques.


Batting Order:

1. Opening Pair:
   - Utilize explosive power hitters with a strong ability to find gaps and clear boundaries early in the innings.
   - Assign players with excellent running between the wickets to capitalize on quick singles and twos.

2. Middle Order:
   - Deploy reliable batsmen capable of stabilizing the innings if early wickets fall.
   - Integrate versatile stroke-makers who can rotate the strike effectively and accelerate the run rate when needed.

3. Finishers:
   - Entrust dynamic finishers with the responsibility to accelerate the scoring rate in the death overs.
   - Position players known for their ability to launch big shots and finish the innings with a flourish.

Bowling Rotations:

1. Opening Attack:
   - Employ aggressive fast bowlers with the ability to generate pace and extract early breakthroughs.
   - Incorporate skillful swing or seam bowlers to exploit any movement available in the initial overs.

2. Spin Options:
   - Introduce spin bowlers with variations to apply pressure in the middle overs and pick up crucial wickets.
   - Utilize spinners who can contain the opposition while also being adept at taking wickets in crucial moments.

3. Death Bowling Specialists:
   - Assign bowlers renowned for their accuracy and execution under pressure to bowl at the death.
   - Implement strategic variations and yorkers to restrict the opposition's scoring opportunities in the final overs.

By implementing this strategic plan tailored to the strengths and weaknesses of our selected players, we aim to maximize our team's chances of success in T20 matches against diverse opponents.

Criteria:

OPENERS                                
PARAMETERS                 DESCRIPTION                                                    CRITERIA
- Batting Average             Average runs scored in an innings                      >30
- Strike Rate                          No of runs scored per 100 balls                       >140
- Innings Batted               Total Innings batted                                              >3
- Boundary %                       % of runs scored in boundaries                      >50
- Batting Position               Order in which the batter played                  < 4

ANCHORS / MIDDLE-ORDER    

PARAMETERS                DESCRIPTION                                                       CRITERIA
Batting Average           Average runs scored in an innings                      >40   
Strike Rate                     No of runs scored per 100 balls                         >125
Innings Batted               Total Innings batted                                             >3
Avg. Balls Faced             Average balls faced by the batter in                 > 20
                                          an innings
 Batting Position             Order in which the batter played                     >2     

FINISHER / LOWER  ORDER ANCHOR

PARAMETERS                 DESCRIPTION                                                            CRITERIA
Batting Average            Average runs scored in an innings                                >25
Strike Rate                       No of runs scored per 100 balls                                   >130
Innings Batted               Total Innings batted                                                          >3
Avg. Balls Faced            Average balls faced by the batter in an innings            >12
Batting Position             Order in which the batter played                                    >4
Innings Bowled            Total Innings Bowled by the bowler                                  >1


ALL-ROUNDERS / LOWER ORDER      

PARAMETERS                     DESCRIPTION                                                      CRITERIA
Batting Average                  Average runs scored in an innings                      >15
Strike Rate                        No of runs scored per 100 balls                              >140
Innings Batted                    Total Innings batted                                                 >2
Batting Position                 Order in which the batter played                          >4
Innings Bowled                  Total Innings bowled                                                >2
Bowling Economy             Average runs allowed per over                                <7
Bowling Strike Rate            Average no. of balls required to take a wicket     <20

SPECIALIST FAST BOWLERS             

PARAMETERS                   DESCRIPTION                                                          CRITERIA
Innings Bowled                Total Innings bowled                                                    >4
Bowling Economy            Average runs allowed per over                                  <7
Bowling Strike Rate       Average no. of balls required to take a wicket          <16
Bowling Style                  The Bowling style of the player                                          = %FAST%
Bowling Average             No. of runs allowed per wicket                                  <20
Dot Ball %                         % of dot balls bowled                                                  >40


































