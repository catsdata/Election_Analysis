# Election_Analysis

## Election Audit Overview

A Colorado Board of Elections employee has requested the following information to complete the election audit of a recent local congressional election.  Election results have been provided via a csv file and the summary below has been requested in a txt file.  

1. Total Number of votes cast
2. Voter turnout for each county
3. Percentage votes for each county
4. County with the highest turnout
5. List of candidates who received votes
6. Total number of votes each candidate received
7. Percentage of votes each candidate won
8. Winner of the election based on popular vote

## Resources

- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.63.2

## Election Audit Results

The analysis of the election shows that:

- There were 369,711 votes case in the election
- The county results were:
    - Jefferson county received 10.5% of the vote and 38,855 total votes
    - Denver county received 82.8% of the vote and 306,055 total votes
    - Arapahoe county received 6.7% of the vote and 24,801 total votes
- Denver county had the highest voter turnout
- The candiddate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 total votes.
    - Diana DeGette received 73.8% of the vote and 272,892 total votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 total votes.
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 total votes.

Data output via command line: 

![dataoutput](https://github.com/catsdata/Election_Analysis/blob/main/analysis/challengerun.PNG)

Text file output can be accessed [HERE](https://github.com/catsdata/Election_Analysis/blob/main/analysis/election_analysis.txt).

## Election Audit Summary

Code for this analysis was processed through [Python](https://github.com/catsdata/Election_Analysis/blob/main/PyPoll_Challenge.py).  This code was written using a csv data file with only three headers: "Ballot ID", "County", and "Candidate".  Provided that election results are processed under the same csv data structure on a county level, this code can be used for any election.  

With additional code modifications and expanded provided election data, further analysis can be done, such as:
- Type of ballot received to understand turnout: Mail-in, Punch Card, and Electronic
- Voter turnout rate using current county population.  
