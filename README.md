# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candiddate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Determine the voter turnout for each county
7. Calculate the percentage of votes from each county out of the total county
8. Determine the county with the highest turnout

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election-Audit Results
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates were
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana DeGette received 73.8% of the vote and 272,892 votes. 
  - Raymon Anthony Doane received 3.1% of the votes and 11,606 votes.
- The winner of the election was:
  - Diana DeGette who received 73.8% of the vote and 272,892 votes.
- The counties were
  - Jefferson
  - Denver
  - Arapahoe
-  The county breakdown was:
  - Jefferson County received 10.5% fo the votes and 38,855 votes
  - Denver County received 82.8% of the votes and 306,055 votes
  - Arapahoe County received 6.7% of the votes and 24,801 votes
- The county with the most votes was
  - Denver which received 82.8% of the votes and 306,055 votes  
- - Prior to creating my with statements and for loops, I initialized a total vote counter. I then created a list that would hold the names of all the candidates, as well as one that would hold the neames of all the counties. I also created a dictionary that would include the candidates as key and votes cast for each candidiate as value. For county, I created a similar dictionary that would include counties as keys and votes cast for each county as values. See the screenshot below for how I set this up.
! [Setting up lists and dictionaries](Resources/County_and_Candidate_Lists_and_Dictionaries.png)

- In order to find the candidate name and county name from each row, I had create a for loop, and loop through different columns. I created two lists called candidate options and ccounty options, which would icrease by a new candididate or new county each time the for loop found a candididate or county now already part of the lists. See screenshot below for how this was executed.
! [Execution of Candidate and County Lists](Resources/Candidate%20and%20County.png)

- As you can see in my output below, I used the lists and dictionaries mentioned above =and the for loop= to be able to get the names of each county and candidiate as well as the amount of votes each recieved. 
! [Output](Resources/Output.png)

  
## Election-Audit Summary
  
