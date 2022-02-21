# Election-Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit if a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4.  the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.64.2

#### The analysis of the election shows that:
- There were 369,711 votes cast in the election.

#### The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
#### the candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana DeGette received 73.8% of the vote and 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
#### The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes.

## Overview of Election Audit
### This section provides insight into the the purpose of this election audit analysis.

The purpose of this analysis is to audit the tabulated results for a US congressional precinct in Colorado. This analysis will provide data on the following:

- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout Working from the data source: election_results.csv file, this analysis utilized for loops and conditional statements with membership and logical operators to find the requested results. Then, printed the results to the command line and saved them to an election_results.txt file.

#### County Results Code
County_Results_Code 

#### Control Flow
1. Add our dependenies
1. Add variables to load and save our source and target files respectively
3. Initialize a total votes counter variable
4. Create empty lists to hold each county and each candidate
5. Create empty dictionary to hold candidate votes and county votes
6. Declare variables to track the winning candidate, vote count and percentage
7. Declare variables to track the largest county and county voter turnout.
8. Using the csv.reader method, read the source file and convert it into a list of dictionaries to fetch candidate name, county name, and vote count for candiatate and county
9. Open the target file and save the election results
10. Write a for loop to get the count from the county dictionary.
11. Calculate the percentage of votes for the county
12. Print the county results to the terminal and save to the target text file.
13. Write an if statement to determine the winning county and get its vote count.
14. Print the county with the largest turnout to the terminal and save to the target text file.
15. Using csv's write method, save the final candidate vote count to the text file.
16. Using an if statement, determine winning vote count, winning percentage, and candidate.

## Election-Audit Results
#### Election Analysis Results
PICTURE

#### Votes Casted in The Congressional Election
- There were 369,711 votes cast in this congressional election. This number agrees with the initial election summary.

#### County Results
- The county with the largest turnout was Denver.
- Jefferson county received 10.5% of the votes and 38,855 total votes.
- Denver county received 82.8% of the votes and 306,055 total votes.
- Arapahoe county received 6.7% of the votes and 24,801 total votes.
- Denver county had the largest voter turnout.

#### Candidate Results
- Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
- Diana DeGette received 73.8% of the vote and 272,892 votes.
- Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- Diana DeGette, who received 73.8% of the vote and 272,892 votes, won the election

## Election-Audit Summary
#### The Proposal

The election commission explores how this script can be used in analyzing any future election, with two examples for modifying the script. 

#### Modification Examples
- Update code so that it is possible for the user to add the name of their csv file and the parent folder of the file. Utilizing the indirect path method, the user would be able to locate the file on the user machine. This allows flexibility in the script to uterlize any csv file with out the need for modifications to the code.

- It is safe to assumption that column names and position will not always be same for all csv files across all preccincts. We may modify our code to allow the user input the column name that contains county name and candidate name. Our script will then attempt to match user input with the column names in the csv file so that date regardless of its differences in naming conventions can be utilized.

Implimenting these two modifications will enable our script to be utilized in any county.

