# Election Analysis

## Overview
A Colorado Election Board employee has requested an audit of recent local election.  The results for each of the candidates and determination of voter turnout in each county are included.

## Results
The analysis of the election data shows:
- There were 369,711 votes cast
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidates results were
    - Charles Casper Stockham received 23.0% of votes with 85,213 number of votes
    - Diana DeGette received 73.8% of votes with 272,892 number of votes
    - Raymon Anthony Doane received 3.1% of votes with 11,606 number of votes
 - The winner was
    - Diana DeGette who received 73.8% of votes with 272,892 number of votes
 
Of the 369,711 votes cast, the analysis of the election data concerning voter turnout show:

 - Jefferson county represents 10.5%  of the votes with 38,855 number of votes
 - Denver county represents 82.8%  of the votes with 306,055 number of votes
 - Arapahoe county represents  6.7% of the votes with 24,801 number of votes

Denver county had the largest turnout.

## Summary
 The code was mostly data driven.  The names of counties and candidates were read from the data and were not hardcoded.  The processing was efficiently performed by with a single pass through the data.

 There were two elements of hardcoding:
 ```
# Add a variable to load a file from a path.
file_to_load = os.path.join("Resources", "election_results.csv")
# Add a variable to save the file to a path.
file_to_save = os.path.join("analysis", "election_analysis.txt")
```

If these two lines were replaced by a query to the user, the programs could be run on other election results data.

 ### Resources used in this project
-Data source: election_results.csv
-Software Python 3.7.6, Visual Studio Code version 1.74.2
