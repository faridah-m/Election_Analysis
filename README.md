# Election_Analysis

## Project Overview
A Colorado Board of Elctions employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election show that:
- There were "x" votes cast in the election
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received "23.0%" of the vote and "85,213" number of votes.
  - Diana DeGette received "73.8%" of the vote and "272,892" number of votes.
  - Raymon Anthony Doane received "3.1%" of the vote and "11,606" number of votes.
- The winner of the election was:
  - Diana DeGette received "73.8%" of the vote and "272,892" number of vote.
 
## Challenge Overview
The objective of the Challenge was to provide the Election Commission some additional data to complete audit an audit that they have been carrying out:
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

The results from the above investigation were to be provided as follows:
- Deliverable 1: The Election Results Printed to the Command Line
- Deliverable 2: The Election Results Saved to a Text File
- Deliverable 3: A written Analysis of the Election Audit (README.md)

### Election Audit Results
#### Deliverable 1
The following Election results were obtained from the VS Studio Code Command Line:
![Image](https://github.com/faridah-m/Election_Analysis/blob/main/Delieverable_1_CommmandLine.PNG)

#### Deliverable 2
The following Election results were written to the Election Analysis Text File:
![Image](https://github.com/faridah-m/Election_Analysis/blob/main/Deliverable_2_TXTFile.PNG)

### Election Audit Summary
The script that we used to produce the above results is a highly versatile script that can be re-factored and used to produce additional information as required:
- To use this script for another election, we would need to provide a new Election_Results.csv file that has the columns: Ballot ID, County and Candidate. Once this file is entered as input, the script will read the new file and use the same logic as in the current file to provide fresh output with little to no modification.

