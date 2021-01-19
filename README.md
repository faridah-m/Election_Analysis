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
The following results were obtained from the script:

- How many votes were cast in this congressional election? **369,711**
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
   
   |County | Vote Percentage |County Votes |
   |-------|-----------------|------------|
  |Jefferson| 10.5% |(38,855)|
  |Denver| 82.8% |(306,055)|
  |Arapahoe| 6.7% |(24,801)|
  
- Which county had the largest number of votes? **Denver**
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

|Candidate | Vote Percentage | Votes |
|-------|-----------------|------------|
|Charles Casper Stockham| 23.0%| (85,213)|
|Diana DeGette| 73.8%| (272,892)|
|Raymon Anthony Doane| 3.1%| (11,606)|

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes? **Diana DeGette: 73.8% (272,892)**

#### Deliverable 1
The following Election results were obtained from the VS Studio Code Command Line:
![Image](https://github.com/faridah-m/Election_Analysis/blob/main/Delieverable_1_CommmandLine.PNG)

#### Deliverable 2
The following Election results were written to the Election Analysis Text File:
![Image](https://github.com/faridah-m/Election_Analysis/blob/main/Deliverable_2_TXTFile.PNG)

### Election Audit Summary
The script that we used to produce the above results is a highly versatile script that can be re-factored and used to produce additional information as required:
- To use this script for another election, we would need to provide a new Election_Results.csv file that has the columns: Ballot ID, County and Candidate. Once this file is entered as input, the script will read the new file and use the same logic as in the current file to provide fresh output with little to no modification.
- If we consider a larger election, such as a presidential election, in which we have an Election_Results.csv file with additional columns such as State and Party. We can perform an analysis similar to the County Analysis, for the State Analysis by adding sections that will count the number of votes per State.

