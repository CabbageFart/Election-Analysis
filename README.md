# Election-Analysis
![image](https://user-images.githubusercontent.com/111661058/190298041-26a1b5c4-b5b9-40ab-b888-427d0ac5cb9b.png)

## Project Overview
A Colorado Board of election manager has asked me to create an algorithm to assist the confirmation and analysis on a recent local election in the great state of Colorado. In order to accomplish this task he has assigned Tom to help guide me through this process. THis process includes several tasks that must be completely in a timely manner.

1. Calculate the total number of votes cast.
2. Calculate the toal number of votes cast per county.
3. Calculate the percentage of votes cast per cuonty.
4. Determine which county had the most votes cast.
5. Get a complete list of candidates who recieved votes.
6. Calculate the total number of votes each candidate recieved.
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular vote.

## Resources
![image](https://user-images.githubusercontent.com/111661058/190241101-2f4c0000-f305-4757-b5bd-24408bd619cb.png)  **3.6.1** ![image](https://user-images.githubusercontent.com/111661058/190241317-3b15dfe8-daff-4bc1-867f-3960321b5aa1.png)  **1.38.1**


-Data Source: election_results.csv

## Election Audit Results
  * There were a total of 369,711 votes cast in this years election
  * 369,711 votes broken down by county:
      -Jefferson county 10.5%   38,855 votes
      -Denver county    82.8%  306,055 votes
      -Arapahoe county   6.7%   24,801 votes
  * Denver had the overwhelming largest number of votes
  * Candidates recieving votes:
      -Charles Casper Stockham  23.0%   85,213 votes
      -Diana DeGette            73.8%  272,892 votes
      -Raymon Anthony Doanne     3.1%   11,606 votes
  * Diane DeGette won by a landslide with 272,892 votes. **73.8%**
  
## Election-Audit Summary
In the future, with this script, you wil be able to sort a .csv file for any local election. As you have seen this algorithm easily prints out all the information you need about current elections given the .csv is set up the same way. If it's not set up the same then you would only have to change a few lines of code:

```candidate_name = row[2]```
   ```county_name = row[1]```  Changing these two row values [ ] to access the correct "Columns" in your .csv file should be all you need to do.


You can also use the vote counts from each county to compare to population data to get voter turnout percentage. Then during the next election cycle you will know where to put your efforts during the campaign process. 

