# Election_Analysis

## Overview of Election Audit
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Get a complete list of counties where votes were casted.
4. Calculate the voter turnout for each conty.
5. Calculate The percentage of votes from each county out of the total count.
6. Determine The county with the highest turnout.
7. Calculate the total number of votes each candidate received.
8. Calculate the percentage of votes each candidate won.
9. Determine he winner of the election based on popular vote.

## Resources
- Data Source: election_resu;ts.csv
- Software: Python 3.7.6, Visual Code, 1.49.3

## Election-Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The counties where votes were casted were:
  - Jefferson
  - Denver
  - Arapahoe
- The voter turnout for each county was:
  - Jefferson had 10.5% of the total votes and 38,855 number od votes.
  - Denver had 82.8% of the total votes and 306,055 number od votes.
  - Arapahoe had 5.7% of the total votes and 24,801 number od votes.
- Denver had the largest number of votes. 
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.
  
### Output on Terminal

![Terminal](/Terminal.png)

## Election-Audit Summary

The script used in this process is very flexible, and can be used for other elections with small modifications:

- By changing the resource CSV file by another with the same format, we can have this analysis done for any other state.
- Also by changing the resource CSV file, we can run this analysis for any other election in following years
- With small modifications on the script, it is also vety easy to produce how many votes each candidate received per county and the correponding percentage.

