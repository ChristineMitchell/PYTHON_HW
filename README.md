# PYTHON_HW
Election Analysis

## Project Overview

A Colorado Board of Elections employee requested your help in completing an election audit of a recent local congressional election. The following tasks are to be included in the completed election audit.

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote.

## Resources

Data Source: election_results.csv
Software: Python 3.8.3, Visual Studio Code 1.46.0

## Summary

The analysis of the election show that:
* There were 369,711 votes cast in the election.
* The candidates were:
  * Charles Casper Stockham
  * Diana DeGette
  * Raymon Anthony Doane
* The candidate results were:
  * Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  * Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  * Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
* The winner of the election was:
  * Diana DeGette, who received 272,892 number of votes, 73.8% of the total votes cast in the election.

## Challenge Overview

The election commission has requested some additional data, rolled up to the county level, to complete the audit:

1. Calculate the voter turnout for each county.
2. Calculate the percentage of votes each county contributed to the election.
3. Determine which county had the largest turnout.

## Challenge Summary

* Of the 369,711 casted votes, we can observe the distribution of the voter turnout between the counties:
  * Jefferson County had 10.5% of the votes, totaling 38,855 actual votes.
  * Denver County had 82.8% of the votes, totaling 306,055 actual votes. 
  * Araphoe County had 6.7% of the votes, totaling 24,801 actual votes. 
* Hence, Denver had the largest voter turnout.

We can certainly refactor our script and apply it to future elections to better understand voter turn-out. For example, we could incorporate additional data and parse it out by age, income, gender, or campaign issues by assigning any one of these elements a variable, establish a counter for that variable, and establish variable brackets to roll up the results to. 

