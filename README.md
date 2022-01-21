# Election_Analysis
Election Analysis in Python

## Overview of Election Audit: 
A Colorado Board of Elections has given task to audit recent congressional election results and find total number of votes, popular/winning candidate basis votes received by each candidate, percentage of votes received by each candidate and voting turnover in each county. 

## Election-Audit Results: 
Please find the complete analysis of the election audit as below in bullet points:
 
    * Total 369,711 votes were cast in the congressional election held in 3 counties. There were 3 candidates running for the election and one candidate swept the election with majority votes of 73.8%. Code used in the Py to count total_votes is "total_votes = 0"(initializing vote counter) and "total_votes += 1"(adding to the total vote count)
    
    * Total number of votes and the percentage of total votes for each county is as below:

      County Votes:
      Jefferson: 10.5% (38,855)
      Denver: 82.8% (306,055)
      Arapahoe: 6.7% (24,801)
 
    * County with highest number of vote is "Denver" with the total number of votes as 306,055 which constitutes for 82.8% of the total vote
    
    * Total number of votes and the percentage of votes for each candidate is as below:
      -------------------------
      Total Votes: 369,711
      -------------------------
      County Votes:
      Jefferson: 10.5% (38,855)
      Denver: 82.8% (306,055)
      Arapahoe: 6.7% (24,801)
      _________________________________

    * "Diana DeGette" won this election with the total vote count of 272,892 and the percentage of vote received is 73.8%
    -------------------------
    Winner: Diana DeGette
    Winning Vote Count: 272,892
    Winning Percentage: 73.8%
    -------------------------
## Election-Audit Summary
This is just to bring it to your notice that this code can be used with other data base to do election analysis but with some changes on the path this file is saved and also some coding changes which I will try to explain in detail below:

    1) You will have to make 2 different folders as 
    
    
    Resources" and "analysis" and save this coding on the same path where you made these 2 folders. Also, save your database (on which you want to do the analysis) in the "Resources" folder and change the name of the database/file to election_results.csv

    2) You will have to change the Row number on the line 47 of this coding file. The Row number that you need to enter will be the base/criteria on which you want to do the analysis. Let's take this database csv file as an example to understand further. If you want to run your analysis on the "County" then your ROW will be [1] and if you want to run your analysis on the Candidates then your ROW will be [2].
    
    3) Also, your final result should automatically get printed on the "election_results.txt" file in the analysis folder. After running the code, if the codes does not automacially created "election_results.txt" file in the anaysis folder, then you will have to create a new TEXT file with the name "election_results.txt" so that the final results gets printed withour any issues.










