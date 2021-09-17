# Election_Analysis

## Project Overview
A Colorado Board of Elctions Employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a compleyte list of candidates who receved votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.8.8, Visual Studio Code 1.60.0

## Summary
The analysis of the election show that:

- There were 369,711 votes cast in the election.

- The counties present on this count were:
    - Jefferson.
    - Denver.
    - Arapahoe.

- The county results were:
    - Jefferson County had 10.5% of the vote and 38,855 votes.
    - Denver County had 82.8% of the vote and 306,055 votes.
    - Arapahoe County had 6.7% of the vote and 24,801 votes.

- The county with the largets number of votes was:
-   - Denver County, with 82.8% of the vote and 306,055 votes.

- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane

- The candidates results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
    - Diana DeGette received 73.8% of the vote and 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.

- The winner of the election was:
    - Candidate Diana DeGette, who received 73.8% of the vote and 272,892 votes.

## Election Audit Summary

This script currently uses a source file that is composed of the Ballot ID, County and Candidate to which vote was cast. There are a few ways we can change the script to provide further analysis on the data.

1. The first one I can think of is adding a column to the election_results.csv file with the timestamp of when the vote was cast. The script could then be adjusted to analyze trends about when voters vote and at what period of the day.

2. Another type of analysis can be done is by adding a column to the election_results.csv file with the date of birth of the voter, assuming that this is allowed by law. After adjusting the script, we would be able to find if there are voters of specifc age range that voted on an specific candidate or the votes were disperse through all the ages. In other words, we would be able to finds voting trends by age ranges.
