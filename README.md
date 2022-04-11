# Election_Analysis

## Overview of Election Audit
A Colorado Board of Elections employee has given the following task to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Calculate the voter turnout for each county.
3. Calculate the percentage of votes from each county.
4. Determine the county with the highest turnout.
5. Get a complete list of candidates who received the votes.
6. Calculate the total number of votes each candidate received.
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular vote.

## Resources
- Date Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.66.0

## Election-Audit Results
The analysis of the elction show that:
- There were 369,711 votes cast in the election.
- The different voting counties were:
   - Jefferson
   - Denver
   - Arapahoe
- The breakdown of votes by county were:
   - Jefferson County had 10.5% of the votes with 38,855 number of votes.
   - Denver County had 82.8% of the votes with 306,055 number of votes.
   - Arapahoe County had 6.7% of the votes with 24,801 number of votes.
- **The largest county turnout was Denver.**
- The candidates were:
   - Charles Casper Stockham
   - Diana DeGette
   - Raymon Anthony Doane
- The candidate results were:
   - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
   - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
   - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- **The winning candidate was:**
   - **Diana Gette who received 73.8% of the vote and 272,892 number of votes.**
<img width="289" alt="Screen Shot 2022-04-07 at 12 36 29 PM" src="https://user-images.githubusercontent.com/101950175/162282647-c9d2a70b-a417-4eb7-9242-0a68c7e03d99.png">

##Election-Audit Summary
This script came be used (with some modifications) for any future elections.  You would be able to take this code - found [here](https://github.com/AimeeJLewis/Election_Analysis/blob/main/PyPoll_Challenge.py), and modify to find the voters demographics for example. Instead of figuring out what county, you could modify the code to look at the age demographics per vote by setting the parameters for what age demographic groups you'd like to look at and utilizing a for loop and if/then statements.  You could also modify this code for individual ballot/measure results to find the winning results of each measure on a ballot by utilizing a if/then statement for a yes/no scenario.  Overall you can utilize this code as a starting point for any election and can modify the script to find the results you are looking for.

